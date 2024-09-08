# javaScriptproject
Car Rental Management System
Introduction
The Car Rental Management System is a JavaScript application designed to manage car rentals. It handles car fleet management, rentals, returns, and charges, allowing users to add cars, rent and return them, and calculate rental charges. This system demonstrates the use of JavaScript and Node.js to build a functional backend application.

Project Type
Backend

Deployed App
Currently, this project does not have a deployed version. It is a local Node.js application.

Directory Structure
car-rental-management/ ├─ carrental.js

Features
Add New Cars to the Fleet: Add cars to the fleet with properties such as model, type, and rental rate per day.
Rent a Car to a Customer: Rent a car to a customer, updating the car’s availability and recording rental details.
Return a Rented Car: Return a rented car, updating the car’s availability and removing the rental record.
Calculate Rental Charges: Calculate the total rental charges based on the rental duration and rate per day.
Display All Available Cars for Rent: List all cars that are currently available for rent.
Design Decisions or Assumptions
Modular Code: The code is modularized to manage the car rental system effectively.
Hard-Coded Data: Example data is hard-coded for demonstration and testing purposes.
JavaScript: JavaScript is used for implementing the system logic and functionality.
Installation & Getting Started
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/car-rental-management.git
Navigate into the project directory:
bash
Copy code
cd car-rental-management
Install Node.js if it's not already installed.
Initialize the project (if not already initialized):
bash
Copy code
npm init -y
Create the necessary file (carrental.js) and add the code as described in the instructions.
Usage
Run the application:
bash
Copy code
node carrental.js
Test the functionality:
Add sample data for cars and rentals.
Call methods to add cars, rent and return them, and calculate charges.
Log results to the console to verify functionality.
Credentials
No authentication is required for this local application.

APIs Used
No external APIs are used in this project.

API Endpoints
This project does not include an API as it is a local Node.js application.

Technology Stack
Node.js: JavaScript runtime used for building the application.
JavaScript: Programming language used to develop the backend logic.
Code Structure and Testing
CarRental Class: Defined in carrental.js, handles all rental logic.

addCar(model, type, ratePerDay): Adds a new car to the fleet.
rentCar(model, customerName, duration): Rents out a car to a customer.
returnCar(model): Returns a rented car to the fleet.
calculateCharges(model): Calculates the total rental charges for a specific car.
displayAvailableCars(): Displays all cars that are available for rent.
Testing: Use the methods with hard-coded data to verify functionality and log results to the console.

Commenting
Detailed comments are included throughout the code to explain the functionality and usage of each method in the CarRental class.
