# AI Bus Crowd Density Monitoring and Smart Seat Booking System

## Project Overview

Students often face overcrowding in college buses, and seats are commonly reserved using bags or books. This results in discomfort, unfair seating, and confusion during boarding.

This system provides real-time seat availability and a structured booking process. Students can reserve a seat before boarding, and they can view updated crowd levels for each bus. The aim is to reduce overcrowding, ensure fair seating, and support the transport department with clear data.

# Key Features
## Feature	                                                                    Description
Smart Seat Booking	                                               Students can book a seat before boarding.
Live Crowd Density	                                               Displays seat occupancy levels (Low, Medium, High).
Route and Timing Display	                                       Uses official college bus routes and schedules.
Booking Records	                                                   Maintains booking history for each register number.
Capacity Display	                                               Shows total, booked, and remaining seats.
Modern Interface	                                               Clean and simple dashboard with organized layout.

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
