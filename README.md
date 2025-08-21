
# 🚌 Bus Reservation System (C Language)

A simple terminal-based bus reservation system written in C.

This project allows users to:

- 🔐 Register and log in
- 🪑 View available seats (1 bus with fixed seats)
- 🧾 Book a seat and enter passenger details
- ❌ Cancel a booking
- 📄 View all bookings

---

## 🚀 How to Run

### 🐧 On Linux/macOS:
```bash
gcc bus_reservation.c -o bus_reservation
./bus_reservation
````

### 🪟 On Windows (using MinGW or GCC):

```bash
gcc bus_reservation.c -o bus_reservation.exe
bus_reservation.exe
```

> 💡 Make sure required `.txt` files (like `users.txt`, `bookings.txt`, `seatList.txt`) are in the same folder as the executable.

---

## 📁 Files Used

* `bus_reservation.c` – Main program file
* `users.txt` – Stores registered user credentials
* `bookings.txt` – Stores seat booking info
* `seatList.txt` – Tracks seat availability

---

## 🧠 Concepts Used

* Arrays for seat tracking
* Linked lists for managing user and booking data
* File I/O for persistent storage
* Basic authentication (username/password)

---

## ⚠️ Limitations

* Only one bus is supported
* No encryption for passwords
* No graphical interface

---

## 👥 Team

This project was developed by a group of 4 students as part of an academic assignment.

---
