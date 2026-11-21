# Hotel Room Booking System
### (Using Java & Data Structures)

> **Course Code:** RU-200-01-00029  
> **Course Name:** Object Oriented Programming with Java  
> **Session:** 2026–27  
> **University:** School of Computer Science and Engineering, Rungta International Skills University, Bhilai (CG)  

---

## 📌 Project Overview
The **Hotel Room Booking System** is a Java application designed to simulate front-desk operations of a hotel. Built using Object-Oriented Programming (OOP) concepts and foundational Data Structures and Algorithms (DSA), it allows users to manage room records, search and sort rooms, make reservations, check availability in real time, and compute booking charges.

---

## 👤 Student Information
- **Student Name:** Nitin Kumar
- **Roll / University ID:** RU-25-10909
- **Project Number:** 18
- **Program:** Bachelor of Technology in Computer Science & Engineering with AI and ML (in association with IBM)
- **Under the Guidance of:** Mr. Santanu Sasmal (IBM SME and EXPERT)

---

## 📄 Project Documentation
- **Interim Report (PDF):** [Nitin-kumar_10909.pdf](./Nitin-kumar_10909.pdf)

---

## 🚀 Key Features
- **View Rooms:** Displays comprehensive room details including room number, category/type, price per night, and current availability status.
- **Search Rooms:** Search for specific rooms or bookings using identifier attributes.
- **Sort Rooms:** Sorts room inventories based on selected criteria (e.g., price or room number).
- **Reservation Processing:** Verifies real-time room availability, calculates `price × nights`, confirms reservations, generates booking IDs, and updates status.
- **Booking Retrieval:** Rapidly looks up booking summaries using unique Booking IDs.

---

## 💡 DSA & OOP Architecture
- **`ArrayList<Room>` & `ArrayList<Booking>`:** Dynamic sequential collections for room inventory and customer reservations.
- **`HashMap<String, Booking>`:** Hash table mapping each unique Booking ID to its reservation object for $O(1)$ fast lookups.
- **Searching & Sorting Algorithms:** Custom traversal and sorting logic to filter and arrange inventory.
- **OOP Principles:** Clean separation of concerns with encapsulated classes:
  - `Room`: Manages individual room attributes and availability state.
  - `Booking`: Encapsulates reservation details, customer data, duration, and calculated charges.
  - `HotelBookingSystem`: Coordinates collections, search/sort algorithms, and interactive menu operations.

---

## 📂 Project Roadmap
- [x] Interim Project Report & Documentation (`Nitin-kumar_10909.pdf`)
- [ ] Source Code Implementation (`src/`)
- [ ] Project Presentation Slide Deck (`PPT/`)
