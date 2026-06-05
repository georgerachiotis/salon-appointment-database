# Salon Appointment Database

A command-line salon appointment scheduling application built with **Bash** and **PostgreSQL** as part of the freeCodeCamp Relational Database Certification.

## Overview

This project simulates a salon booking system where customers can schedule appointments for available services through an interactive terminal interface.

The application stores customer information, available services, and appointment data in a PostgreSQL relational database.

## Features

* Display available salon services
* Register new customers
* Search existing customers by phone number
* Schedule appointments
* Store appointment records in a PostgreSQL database
* Use foreign key relationships between tables

## Database Structure

### Customers

* customer_id (Primary Key)
* name
* phone (Unique)

### Services

* service_id (Primary Key)
* name

### Appointments

* appointment_id (Primary Key)
* customer_id (Foreign Key)
* service_id (Foreign Key)
* time

## Technologies Used

* Bash
* PostgreSQL
* SQL

## Learning Objectives

This project demonstrates:

* Relational database design
* Primary and foreign keys
* SQL queries and data manipulation
* Bash scripting
* User input validation
* Database integration with shell scripts

