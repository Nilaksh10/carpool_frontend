🚗 Carpooling Application
This is a Carpooling Application built using HTML, CSS, JavaScript, and Bootstrap for the frontend, with a backend powered by PHP (Laravel Framework) and MySQL. The application enables users to sign up or log in and choose to act as either a Driver or a Rider. Drivers can add ride details, while riders can search for available rides based on location filters.

🛠 Features
User Features
Authentication:
Users can sign up and log in securely.
Driver Interface:
Drivers can:
Enter their starting location, destination, and available seats.
Submit their ride details to the database.
Rider Interface:
Riders can:
Search for available rides based on location filters.
View a list of matching rides with details about the driver and availability.
Backend Features
MySQL Database Integration:
Stores user accounts, ride details, and location information.
Laravel Framework:
Provides a robust backend with RESTful API endpoints for user authentication, ride management, and filtering rides.
Ride Matching Algorithm:
Filters rides based on location and availability criteria.
🛠 Technologies Used
Frontend
HTML5
CSS3
JavaScript (ES6)
Bootstrap
Backend
PHP (Laravel Framework)
MySQL
🗃 Database Schema
Users Table:
id, name, email, password, role (Driver/Rider).
Rides Table:
id, driver_id, start_location, destination, available_seats, created_at.
🖥 Application Workflow
User Registration & Login

Users register as drivers or riders and log in to access the application.
Driver Workflow

Drivers provide ride details, including starting point, destination, and available seats.
Ride details are saved to the database.
Rider Workflow

Riders search for rides by entering their starting point and destination.
A filtered list of rides is displayed, based on the matching criteria.
🎯 Future Enhancements
Add real-time ride matching using WebSockets.
Implement Google Maps API for location-based ride search.
Add payment gateway integration for booking rides.
Improve UI/UX with modern frameworks like React or Vue.js.
