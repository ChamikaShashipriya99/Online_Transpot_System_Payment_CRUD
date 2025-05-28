# RideEase

RideEase is a web application for booking rides and managing payments. This is a simple online cab service application.

## Features

* User registration and login
* Cab booking
* Payment processing
* Admin panel for managing users, cabs, and bookings

## Technologies Used

* Java
* JSP
* Servlet
* MySQL

## Setup and Run

1. Clone the repository.
2. Import the project into your favorite IDE.
3. Create a MySQL database named `transport_DB`.
4. Import the `transport_DB.sql` file into your database.
5. Configure the database connection in `src/main/java/com/oop/util/DBConnect.java`.
6. Build the project using a build tool like Maven or Ant.
7. Deploy the generated WAR file to a Tomcat server.
8. Access the application in your web browser, typically at `http://localhost:8080/<your-project-name>`.

## Project Structure

* `src/main/java`: Contains the Java source code for the application, including servlets, models, and utility classes.
* `src/main/webapp`: Contains the web application files, such as JSPs, HTML, CSS, and JavaScript.
* `transport_DB.sql`: Contains the SQL script for creating the database schema and tables.
* `build/`: Contains the compiled Java classes and other build artifacts.
* `WebContent/` (Note: This might be `webapp/` depending on project configuration): Contains web resources like JSPs, images, and client-side scripts.

## Usage

1.  **Register and Login:** New users need to register to create an account. Existing users can log in with their credentials.
2.  **Booking a Ride:**
    *   Navigate to the booking section.
    *   Enter pickup location, destination, and preferred time.
    *   Select a cab type.
    *   Confirm the booking.
3.  **Viewing Booking Details:**
    *   Access your user dashboard or booking history.
    *   View details of past and upcoming rides.
4.  **Making a Payment:**
    *   After a ride is completed, go to the payment section.
    *   Select the booking for which payment is due.
    *   Choose a payment method and complete the transaction.
5.  **Admin Functionalities:**
    *   Admins can log in to a separate admin panel.
    *   Manage users, drivers, cabs, and view all bookings.
    *   Handle payment disputes and refunds.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
