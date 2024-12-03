Overview

The Flight Booking System is a Java- based application that allows users to manage flight bookings efficiently. Users can log in or create an account, search for available flights, book seats, and view their booking history. The system manages destinations, dates, and times, ensuring that seats are allocated correctly. It also saves user data persistently in a file for future retrieval.

Features

• User Management:

Create new accounts with a username and password.

Log in with existing credentials.

• Flight Booking:

Book flights for predefined destinations, dates, and times.

Check for seat availability and confirm bookings.

• View Bookings:

• Users can view their booking history with details like destination, date, and time.

• Data Persistence:

User data and booking information are saved in a file (users.txt) for future access.

Technologies Used

• Java: Core programming language.

File I/O: Used for persistent data storage and retrieval.

• Multithreading: Ensures thread-safe operations during booking.

• OOP Principles: Organized code using classes like User, Booking, and FlightManager.


How It Works

1. User Login/Registration:

• The system checks if the user exists in the users.txt file.

If not, the user can register by creating a new account.

2. Flight Management:

• Users can select a destination, date, and time from predefined options.

• The system checks seat availability and processes the booking.

3. Booking Storage:

• Bookings are added to the user's profile and saved to a file for future sessions.

4. Thread Safety:

• Bookings are handled in a synchronized manner to avoid conflicts when multiple users access the system simultaneously.


