# MovieTicketBooking

# Online_Movie_Ticket_Booking_Web_Application
This web application allows users to browse and book movie tickets online. It offers a user-friendly interface for selecting movies, showtimes and seats. The application is designed with both users and admin in mind, providing features such as user registration and authentication, and an admin dashboard for managing movie listings and theaters.

This is a README for a movie ticket booking web application built using .NET Core.
## Team Name: Idea Incubators
## Team Members
- *Abhishek Jamkar*
## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Database Setup](#database-setup)
5. [Running the Application](#running-the-application)
6. [Features](#features)

## Prerequisites
Before getting started, make sure you have the following prerequisites installed on your system:

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [Visual Studio Code](https://code.visualstudio.com/) or any code editor of your choice
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) for database storage
- [Node.js](https://nodejs.org/) for client-side dependencies
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/)

## Installation
1. Clone this repository: `https://github.com/AbhishekJamkar/MovieTicketBooking.git`
2. Open the project in your code editor.


## Configuration
- Configure your database connection string in `appsettings.json`.
- Set up the necessary API keys for services if applicable.

## Database Setup
1. Run migrations to create the database schema:
   - Update-database
   - Add-Migration Migrationname

dotnet ef database update

2. Seed the database with initial data (e.g., movie listings, theaters, etc.).

## Features
- User Registration and Authentication
- Browse Movie Listings
- Select Showtimes
- Seat Selection
- Booking Confirmation
- Admin Dashboard (for managing movies, theaters, etc.)

Remember to replace "your/repo" with the actual GitHub repository URL where the project is hosted, and customize the content and structure according to your project's needs.
