# Car-Rental-System
This Java program implements a console-based Car Rental System that allows users to rent and return cars through an interactive menu. The system consists of four main classes: **`Car`** (representing vehicles with attributes like ID, brand, model, daily price, and availability status), Customer`(storing renter details), `Rental`(managing rental transactions), and `CarRentalSystem` (the core system handling operations like adding cars, renting, and returning). The `Main` class initializes the system with sample cars (Toyota Camry, Honda Accord, and Mahindra Thar) and launches the menu. Users can rent a car (view available options, select a vehicle, specify rental days, and confirm the booking) or return a car (by entering the car ID). The program tracks availability, calculates rental costs, and auto-generates customer IDs while ensuring proper validation (e.g., preventing rentals of unavailable cars). Designed with object-oriented principles, this system efficiently manages inventory, customers, and transactions in a structured, user-friendly manner.

Features

Rental Process:

Customers provide their name

View available cars

Select car by ID

Specify rental duration

Confirm rental with calculated total price

Return Process:

Return car by ID

System verifies car was actually rented

Updates availability status

Data Management:

Tracks all cars, customers, and rentals

Auto-generates customer IDs

Maintains availability status
