# 🚗 Car Rental System  
_A Simple Java Console-Based Car Rental System_  

![Car Rental](https://media.giphy.com/media/3o7abldj0b3rxrZUxW/giphy.gif)  

## 📌 Overview  
The **Car Rental System** is a Java-based console application that allows users to:  
✔️ Rent a car from a list of available cars.  
✔️ Return a rented car.  
✔️ View total rental cost before confirming.  

## 🛠️ Features  
🔹 **Car Management** – Add and list cars with their details.  
🔹 **Customer Handling** – Register customers dynamically.  
🔹 **Rental Processing** – Rent and return cars with availability tracking.  
🔹 **Pricing System** – Calculate rental costs based on duration.  
🔹 **Interactive CLI** – User-friendly console interface.  

## 📂 Project Structure  
```
📦 Car Rental System
 ┣ 📜 Main.java          # Entry point for the application
 ┣ 📜 Car.java           # Car class with rental logic
 ┣ 📜 Customer.java      # Customer information storage
 ┣ 📜 Rental.java        # Rental transaction details
 ┣ 📜 CarRentalSystem.java # Core functionality (rental, return, menu)
```

## 🚀 Installation & Usage  
1️⃣ Clone the repository:  
```bash
git clone https://github.com/your-username/Car-Rental-System.git
cd Car-Rental-System
```
2️⃣ Compile and run the project:  
```bash
javac Main.java
java Main
```
3️⃣ Follow the on-screen menu options to rent/return cars.  

## 🎥 Demo  
📌 Sample Output:  
```
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==
Enter your name: Alex
Available Cars:
C001 - Toyota Camry
C002 - Honda Accord

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==
Customer ID: CUS1
Customer Name: Alex
Car: Toyota Camry
Rental Days: 3
Total Price: $180.00
Confirm rental (Y/N): Y

Car rented successfully.
```

## 🛠️ Technologies Used  
🔹 **Java** – Core programming language  
🔹 **OOP Concepts** – Encapsulation, Polymorphism  
🔹 **Scanner Class** – User input handling  

## 🏆 Future Enhancements  
✅ GUI-based version with JavaFX  
✅ Online database for rental tracking  
✅ Advanced pricing models with discounts  

## 📜 License  
📝 MIT License – Free to use and modify.  

👨‍💻 Developed by **Bhuvan Tenguria** 🎯  
