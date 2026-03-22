# Smart Parking Management System

A console-based Parking Management System developed in C++ to efficiently manage vehicle parking, track slot allocation, and maintain parking records.

---

## Overview

This system allows users to park and manage vehicles across different categories (2-wheelers, 3-wheelers, and 4-wheelers).  
It ensures structured slot allocation, prevents duplicate entries, and maintains real-time parking status.

---

## Features

- 🚗 Supports 2, 3, and 4-wheeler parking with dedicated slot ranges  
- 🔢 Automatic slot allocation based on vehicle type  
- 📊 Real-time parking status display (vehicles, slots, revenue)  
- ❌ Vehicle removal functionality with data update  
- 📁 Stores parking records in a `.doc` file on exit  
- 📞 Input validation for unique vehicle numbers and phone numbers  

---

## System Design

- Total parking slots: 75  
- 25 slots allocated per vehicle category  
- Slot ranges:
  - 1–25: Two-wheelers  
  - 26–50: Three-wheelers  
  - 51–75: Four-wheelers  

- Pricing:
  - 2-Wheeler: ₹50  
  - 3-Wheeler: ₹100  
  - 4-Wheeler: ₹150  

---

## Tech Stack

- Language: C++  
- Concepts Used:
  - STL (vector, set)  
  - File Handling (ofstream)  
  - Input Validation  
  - Control Flow & Menu-driven Programming  

---

## How It Works

1. User selects vehicle type from menu  
2. Enters vehicle details (number, name, phone)  
3. System validates and assigns a slot  
4. Tracks total vehicles and revenue  
5. Allows removal of vehicles  
6. Saves all records to a file before exit  

---

## Output

- Console-based interaction  
- Generates a file: `parking_details.doc` containing:
  - Total vehicles parked  
  - Slot-wise vehicle details  

---

## Learning Outcomes

- Implemented real-world problem using structured programming  
- Gained hands-on experience with STL and file handling  
- Practiced validation logic and data management  

---

## Future Improvements

- GUI-based interface  
- Database integration  
- Online slot booking system  
- Payment gateway integration  

---

## Author

Mukil M  

LinkedIn: https://www.linkedin.com/in/mukil-m-92010m/  
Email: mukilmunnilath@gmail.com
