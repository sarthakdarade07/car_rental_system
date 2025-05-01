# 🚗 Car and Transport Vehicle Rental Management System (C++)

## 📌 Description

This is a **console-based application in C++** for managing a car and transport vehicle rental service. It offers functionalities for both **users** (customers) and **company admins**. The system handles:

- Car bookings and returns
- Transport vehicle bookings
- Car list management (add, remove, view)
- Booking history storage in a file

---

## 👤 Roles

### 1. User
- Can **book a car**.
- Can **return a rented car**.
- Can **book transport vehicles** like Tata Ace or Bolero Pickup.

### 2. Company
- Can **add new cars** to the system.
- Can **remove cars** (unless rented).
- Can **view all car listings** (sorted alphabetically).
- Can **view booking history** (from `Bill.txt`).

---

## 🔧 Features

- Object-oriented design with classes: `company`, `Transport_vehicle`, and `user`.
- Use of STL `vector`, file I/O (`fstream`), and lambda expressions.
- Booking information is stored in a file `Bill.txt`.
- Includes sorting of car list by name.
- Simple exception handling in main menu input.

---

## 🗃️ File Structure

- **Main.cpp** - Contains all class definitions and the `main()` function.
- **Bill.txt** - Auto-generated file that stores customer booking records.

---

## 🚀 How to Run

1. Open a C++ compiler or IDE (e.g., CodeBlocks, VSCode, g++ terminal).
2. Compile the program:
   ```bash
   g++ main.cpp -o rental
