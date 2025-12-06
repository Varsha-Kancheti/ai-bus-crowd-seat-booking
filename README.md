# AI Bus Crowd Density Monitoring and Smart Seat Booking System

## Project Overview

Students often face overcrowding in college buses, and seats are commonly reserved using bags or books. This results in discomfort, unfair seating, and confusion during boarding.

This system provides real-time seat availability and a structured booking process. Students can reserve a seat before boarding, and they can view updated crowd levels for each bus. The aim is to reduce overcrowding, ensure fair seating, and support the transport department with clear data.

# Key Features
## Feature	and  Description
The system provides a structured bus seat booking process that enables students to reserve a seat before boarding, removing the need for rushing or marking seats with bags. It offers real-time seat availability by displaying the total number of seats, seats already booked, and the remaining capacity for each bus trip. Bus crowd levels are monitored and shown clearly as Low, Medium, or High, allowing students to make informed boarding decisions. The platform operates using official route names, bus numbers, and transport timings provided by the institution, ensuring accurate and valid trip information.

Each booking is stored in the system and linked to the student’s register number, which allows verification and provides a record history when needed. The system supports both morning and evening trips, reflecting the regular college transport schedule. All active bus trips are presented in a simple and organized dashboard so that users can quickly view booking status, seat availability, and bus details. Seat numbers are assigned automatically in the order of booking to maintain fairness and avoid manual adjustments. Booking status is recorded as Booked, Cancelled, or Checked-In, ensuring that seat usage and entry can be tracked precisely. The overall interface is designed to be clear and easy to navigate, focusing on accessibility and comfort rather than complex visual elements.
# Technology Used

## Frontend

HTML5

Bootstrap 5

Custom CSS (Dark Theme)

## Backend

Python Flask

Jinja2 Templating

## Database

SQLite

SQLAlchemy ORM

# Folder Structure
ai_bus_booking/
│
├── app.py
├── requirements.txt
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── book.html
│   └── my_bookings.html
│
└── static/
    └── style.css
