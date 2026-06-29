# 🚗 Car Rental System

## 📌 Overview

The Car Rental System is a console-based Java application that allows users to rent and return cars. It is built using Object-Oriented Programming (OOP) concepts such as classes, objects, encapsulation, and collections.

This project demonstrates how a simple rental management system works by maintaining records of cars, customers, and rentals.

---

## ✨ Features

* View available cars
* Rent a car
* Return a rented car
* Customer registration during rental
* Rental price calculation based on number of days
* Prevent renting unavailable cars
* Menu-driven console interface

---

## 🛠️ Technologies Used

* Java
* Object-Oriented Programming (OOP)
* ArrayList
* Scanner Class
* Java Collections Framework

---

## 📂 Project Structure

```
carRented/
│
├── Car.java
├── Customer.java
├── Rental.java
├── CarRentalSystem.java
└── project.java
```

---

## 📖 Class Description

### Car

Represents a car available for rent.

**Attributes**

* Car ID
* Brand
* Model
* Base Price Per Day
* Availability Status

**Methods**

* calculatePrice()
* rent()
* returnCar()
* Getter methods

---

### Customer

Stores customer information.

**Attributes**

* Customer ID
* Customer Name

**Methods**

* Getter methods

---

### Rental

Stores rental details.

**Attributes**

* Car
* Customer
* Rental Days

**Methods**

* Getter methods

---

### CarRentalSystem

Manages the entire rental process.

**Functions**

* Add new cars
* Add customers
* Rent cars
* Return cars
* Display menu

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/CarRentalSystem.git
```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, or VS Code).

3. Compile the project.

```bash
javac project.java
```

4. Run the program.

```bash
java project
```

---

## 📋 Sample Menu

```
===== Car Rental System =====

1. Rent a Car
2. Return a Car
3. Exit

Enter your choice:
```

---

## 💡 Example

### Renting a Car

```
Enter your name:
John

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter Car ID:
C001

Enter Rental Days:
3

Total Price: $180.00

Confirm Rental (Y/N):
Y

Car rented successfully.
```

---

## 📚 OOP Concepts Used

* Encapsulation
* Abstraction
* Object Creation
* Constructors
* Collections (ArrayList)
* Method Invocation

---

## 🚀 Future Improvements

* Login authentication
* Admin panel
* Save data using files or a database (MySQL)
* Search cars by brand or model
* Update/Delete car records
* Payment integration
* Rental history
* Late return fine calculation
* Date-based booking system
* GUI using Java Swing or JavaFX

---

## 🎯 Learning Outcomes

This project helped in understanding:

* Java fundamentals
* Object-Oriented Programming
* Collection Framework
* User input handling
* Console application development
* Basic software design

---

## 👨‍💻 Author

**Priyanshu Singh**

Java Developer 

---

## 📄 License

This project is for educational and learning purposes.
