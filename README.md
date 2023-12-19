# Bus Reservation App in Java

This Java application allows users to make bus reservations. It includes classes for managing buses, bookings, and a main program (`BusDemo.java`) to demonstrate the functionality.

## Table of Contents
- [Files](#files)
- [How to Run](#how-to-run)
- [Classes](#classes)
  - [Bus](#bus-class)
  - [Booking](#booking-class)
  - [BusDemo](#busdemo-class)

## Files

1. **BusDemo.java**
   - Main program demonstrating the bus reservation system.
   - Manages buses and bookings, allowing users to book a seat if available.

2. **Booking.java**
   - Represents a booking with details such as passenger name, bus number, and date.
   - Checks for seat availability based on existing bookings and bus capacity.

3. **Bus.java**
   - Defines the Bus class with attributes like bus number, air conditioning availability, and seating capacity.

## How to Run

1. Ensure you have Java installed on your system.
2. Compile and run the `BusDemo.java` file to execute the bus reservation application.

```bash
javac BusDemo.java
java BusDemo
javac Booking.java
java Booking
javac Bus.java
java Bus
