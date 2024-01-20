# Voting Application

## Introduction

Welcome to the Voting Application project! This application is designed to facilitate the voting process, with separate sections for administrators and users.

## Features

## Admin Section

* View and manage total votes for each political party (PTI, PMLN, PPP).<br>
* Register voters with their names and ID card numbers.<br>
* Register political parties with their names and party heads.<br>

## User Section

* Users can submit their votes for PTI, PMLN, or PPP.<br>
* Checks are in place to ensure users are registered and have not already voted.<br>

## Technologies Used

* Python
* PyQt5 for GUI
* MySQL for database


## Getting Started

1. Install the required dependencies:
    pip install PyQt5 pymysql

2. Set up the MySQL database:
    * Create a MySQL database named votingdb.
    * Import the SQL file (votingdb.sql) provided in the project.

3.Run the application:
    * python main_admin.py  # For Admin Section
    * python main_user.py   # For User Section
