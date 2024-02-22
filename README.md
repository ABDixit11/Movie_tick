# Movie Ticket Booking System

Welcome to the Movie Ticket Booking System repository! This web application is built using HTML, CSS, PHP, and utilizes a MySQL database for managing movie bookings. The system is hosted on an Apache server.

## Table of Contents
- Features
- Installation
- Usage
- Database Setup

## Features
- User-friendly interface for browsing and booking movie tickets.
- Seamless integration of HTML, CSS, and PHP for a responsive design.
- Secure authentication and authorization for user accounts.
- Booking history and ticket confirmation functionalities.
- Integration with a MySQL database for efficient data management.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/movie-ticket-booking.git
## Usage

1. Access the application through your web browser:
    ```bash
    http://localhost/movie-ticket-booking
    ```
2. Browse available movies, select showtimes, and book your tickets.

## Database Setup

1. Create a new MySQL database named `movie_ticket_booking`.
2. Import the SQL dump file included in the `database` directory:
    ```bash
    mysql -u your-username -p movie_ticket_booking < database/movie_ticket_booking.sql
    ```
3. Update the `config.php` file with your MySQL database credentials.
