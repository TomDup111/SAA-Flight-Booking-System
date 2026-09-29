# SAA Flight Booking System

## Project Description

The SAA Flight Booking System is a database project developed for the MDB622 Database Manipulation practical assessment.

The system is designed to manage passenger information, airports, flights, bookings, tickets and payments. The database was created using Microsoft SQL Server and connected to a C# Console Application.

## Technologies Used

- Microsoft SQL Server
- SQL Server Management Studio
- C#
- Visual Studio
- Microsoft.Data.SqlClient
- Git
- GitHub

## Database Tables

The system contains the following tables:

- Airports
- Passengers
- Flights
- Bookings
- BookingPassengers
- Tickets
- Payments

## Main Features

The system can:

- Store airport information
- Store passenger information
- Manage flight information
- Create and manage bookings
- Link passengers to bookings
- Store ticket information
- Store payment information
- Retrieve database records
- Update existing records
- Prevent invalid deletes using foreign key constraints
- Generate reports using SQL joins and aggregate functions
- Connect to the database using a C# Console Application

## Database Relationships

The database uses primary keys and foreign keys to maintain referential integrity.

The BookingPassengers table is used as an associative table between Bookings and Passengers.

The main relationships include:

- Airports to Flights
- Flights to Bookings
- Bookings to BookingPassengers
- Passengers to BookingPassengers
- BookingPassengers to Tickets
- Bookings to Payments

## C# Application

The C# Console Application connects to the SAAFlightBookingDB SQL Server database using Microsoft.Data.SqlClient.

The application retrieves and displays passenger records from the Passengers table.
