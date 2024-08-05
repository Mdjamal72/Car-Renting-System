# Car-Renting-System
Overview
Rent-A-Ride is a Java-based car renting system that runs on the terminal. The project utilizes object-oriented programming (OOP) concepts to manage car rentals, customer information, and rental transactions efficiently.
Features
Car Management: Add and manage cars available for rent.
Customer Management: Register and manage customer information.
Rental Process: Rent cars to customers and calculate rental costs based on rental duration.
Return Process: Return rented cars and update availability status.
Usage
Rent a Car: Choose the option to rent a car, enter your name, select a car from the available list, and specify the rental duration.
Return a Car: Choose the option to return a car, enter the car ID, and confirm the return.
Exit: Choose the exit option to close the application.
Example-
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: John Doe

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==

Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 3
Total Price: $180.00

Confirm rental (Y/N): Y

Car rented successfully.


Project Structure
Main.java: Entry point of the application.
Car.java: Defines the Car class with properties and methods.
Customer.java: Defines the Customer class with properties and methods.
Rental.java: Defines the Rental class that links cars and customers.
CarRentalSystem.java: Manages cars, customers, and rentals; handles user interactions.
