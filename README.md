# Movie Ticket Booking System

## Overview
The Movie Ticket Booking System is designed to streamline the process of booking movie tickets online. Users can log in, select their preferred movie, theater, showtime, and the number of tickets. After finalizing the booking, they can proceed with payment and receive a ticket receipt to present at the theater.

---

## API Documentation

This section provides a detailed guide for developers integrating with the Movie Ticket Booking System API.

### Audience
- **Developers** working to integrate this API with their applications or platforms.

### Platform
- Hosted on **GitHub**, the repository is publicly accessible to provide open access to the project.

---

### Installation Steps

1. **Download the Project**:
    - Clone or download the project from the following GitHub repository: [Online Movie Ticket Booking System](https://github.com/rabakkar/Online-Movie-Ticket-Booking-System).

2. **Download ZIP File**:
    - Download the ZIP file containing the project from GitHub and unzip it on your local server.

3. **Install NetBeans 8.2**:
    - Download and install **NetBeans 8.2 IDE** for working with the Java project.

4. **Install XAMPP**:
    - Download and install **XAMPP** for running Apache and MySQL services.

5. **Start MySQL**:
    - Open XAMPP and click **Start** to ensure MySQL is running.

6. **Database Setup**:
    - Open your browser and go to [phpMyAdmin](http://localhost/phpmyadmin/).
    - Create a new database named `Movie`.
    - Import the `Movie.sql` file located in the project folder into the database.

7. **Open the Project in NetBeans**:
    - Open **NetBeans** and navigate to the unzipped folder to open the `movieticketbooking` project.

8. **Connect the Database**:
    - Ensure that the project is properly connected to the newly created `Movie` database.

---

### Core Components

The API consists of several core components, each playing a vital role in the system:

- **User Login Module**:
    - Handles user authentication, allowing existing users to log in by entering their username and password.

- **User Registration Module**:
    - Allows new users to create accounts by providing personal details such as name, email, and password.

- **Movie Selection Module**:
    - Users can browse and select a movie from the list of currently playing films.

- **Theater and Showtime Selection Module**:
    - Users select the theater where the chosen movie is playing, along with the desired showtime.

- **Ticket Booking Module**:
    - Users specify the number of tickets they want to book, and the system processes their selection.

- **Payment Module**:
    - Supports various payment methods such as credit cards, debit cards, and online wallets.
    
- **Ticket Generation Module**:
    - Upon successful payment, a ticket receipt is generated containing all booking details, which can be printed or displayed on the user’s device for admission.

---


### System Architecture

The project follows a modular architecture to ensure scalability and easy maintenance. Below is a high-level overview of the system architecture:

1. **User Interface**: Interacts with the user to collect input for logging in, booking tickets, and processing payments.
2. **API Layer**: Exposes endpoints for user authentication, movie selection, ticket booking, and payment processing.
3. **Database**: Stores user data, movie details, showtimes, theaters, and booking records.
4. **Payment Gateway**: Integrates with third-party payment services to handle transactions securely.
5. **Ticket Generation**: After successful payment, a digital ticket is generated for the user.

---

By following this guide, developers can effectively integrate the Movie Ticket Booking System into their applications.
