---
title: "Flight Booking System"
---


This project is a complete client–server flight booking system built entirely in Java.
<br>
This project used
Java Sockets & Multi-threading for client–server communication,
<br>
Swing GUI for user interaction,
<br>
Text-file storage for users, flights, and booking history,
<br>
Object-oriented design.
<br>
<br>


The system simulates a real airline reservation environment.
It uses a server that manages all flights, users, authentication, discounts, and file updates, while the client side provides a GUI where users and admins can access the system.

<br>
<br>
Key Features
<br><br>

1. User Authentication

Sign In, Sign Up, and Admin Login

<br><br>
2. Booking Flights

Users can book flights in two ways: Using Passport - Using Visa

The system loads available destinations from text files

Then it shows: Matching countries - Available flights and

flight details (ID, date, cost, class, time)
<br><br>
3. Discount System

A unique discount mechanism:

Users receive discounts based on their previous flights

The server checks each customer’s file:

If user took:

3 or more High-class flights → 50% discount

3 or more Business-class flights → 30% discount

Ticket price updated dynamically on the server
<br><br>
4. File-Based Storage System

All data is stored in structured text files:

Flights.txt (All available flights)

Passengers.txt (Users & balances)

*_previous_flights.txt (History for each user)

The server includes custom functions to:

Modify a specific line in a file

Remove lines

Rewrite files with updated values
<br><br>
5. Balance & Payment Handling

Server checks user’s balance before booking

Updates the file with the new balance

Saves the booked flight to the user’s history file
<br><br>
6. Admin Panel

When signed in as admin, the system allows:

Adding flights

Updating flights

Removing flights

Admin operations modify the flight list in Flights.txt.
<br><br>
7. Multi-threaded Server

The server uses threads to handle multiple client connections

<br>
<br>
8. Swing GUI

All user interactions use pop-ups:

Input dialogs

Multi-choice



Screenshots
{% include figure image_path="/assets/images/FlightSystem/sp1.png" caption="Sign in/Sign up page" %}
{% include figure image_path="/assets/images/FlightSystem/sp2.png" caption="Booking page" %}
{% include figure image_path="/assets/images/FlightSystem/sp3.png" caption="Discount page" %}
{% include figure image_path="/assets/images/FlightSystem/sp4.png" caption="Admin page" %}

