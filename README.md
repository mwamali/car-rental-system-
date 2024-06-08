# car-rental-system-
A simple Java-based Car Rental System that allows users to manage cars and customers, rent and return cars, and view available cars. This project provides a basic command-line interface to demonstrate the core functionalities of a car rental service, including adding cars, registering customers, and handling car rentals and returns.

# Car Rental System

This project is a simple Car Rental System implemented in Java. It allows users to add cars, register customers, rent and return cars, and display available cars.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Classes](#classes)
  - [CarRentalSystem](#carrentalsystem)
  - [RentalAgency](#rentalagency)
  - [Car](#car)
  - [Customer](#customer)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/mwamali/car-rental-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd car-rental-system
   ```

3. Compile the Java files:
   ```bash
   javac CarRentalSystem.java
   ```

4. Run the program:
   ```bash
   java CarRentalSystem
   ```

## Usage

The Car Rental System provides the following menu options:

1. **Add Car**: Allows you to add a new car to the system.
2. **Register Customer**: Allows you to register a new customer.
3. **Rent a Car**: Allows a registered customer to rent an available car.
4. **Return a Car**: Allows a customer to return a rented car.
5. **Display Available Cars**: Displays all cars that are currently available for rent.
6. **Exit**: Exits the Car Rental System.

## Classes

### CarRentalSystem

The `CarRentalSystem` class contains the `main` method and the main menu logic. It interacts with the `RentalAgency` class to perform various operations.

### RentalAgency

The `RentalAgency` class manages the cars and customers. It provides methods to add cars, register customers, rent cars, return cars, and display available cars.

### Car

The `Car` class represents a car with attributes such as make, model, year, daily rate, and rental status. It provides methods to get the car's make, check if it is rented, and set its rental status.

### Customer

The `Customer` class represents a customer with attributes such as name, driver's license, and phone number. It provides a method to get the customer's name.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
