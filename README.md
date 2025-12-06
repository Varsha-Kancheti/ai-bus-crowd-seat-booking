# AI Bus Crowd Density Monitoring and Smart Seat Booking System

## Project Overview

Students often face overcrowding in college buses, and seats are commonly reserved using bags or books. This results in discomfort, unfair seating, and confusion during boarding.

This system provides real-time seat availability and a structured booking process. Students can reserve a seat before boarding, and they can view updated crowd levels for each bus. The aim is to reduce overcrowding, ensure fair seating, and support the transport department with clear data.

# Key Features
## Feature	and  Description
The system provides a structured bus seat booking process that enables students to reserve a seat before boarding, removing the need for rushing or marking seats with bags. It offers real-time seat availability by displaying the total number of seats, seats already booked, and the remaining capacity for each bus trip. Bus crowd levels are monitored and shown clearly as Low, Medium, or High, allowing students to make informed boarding decisions. The platform operates using official route names, bus numbers, and transport timings provided by the institution, ensuring accurate and valid trip information.

Each booking is stored in the system and linked to the student’s register number, which allows verification and provides a record history when needed. The system supports both morning and evening trips, reflecting the regular college transport schedule. All active bus trips are presented in a simple and organized dashboard so that users can quickly view booking status, seat availability, and bus details. Seat numbers are assigned automatically in the order of booking to maintain fairness and avoid manual adjustments. Booking status is recorded as Booked, Cancelled, or Checked-In, ensuring that seat usage and entry can be tracked precisely. The overall interface is designed to be clear and easy to navigate, focusing on accessibility and comfort rather than complex visual elements.

# Future Enhancements

The system can be extended with QR-based verification so that each booking generates a scannable code at the time of entry. Future upgrades may also include predictive crowd analysis, where booking patterns and route usage data help forecast busy routes and periods. A dedicated transport administration panel can be introduced to allow authorized staff members to manage routes, bus capacities, trips, and booking logs directly. Additional features such as seat-full alerts or notifications may inform students when a bus is nearing full capacity. An Android-based mobile application may also be developed to make booking access faster and more convenient. The system can further evolve to support multi-trip planning, such as special schedules during examinations or extra buses arranged for high-demand days.
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
ai_bus_booking
app.py – main application and backend logic

templates – contains HTML pages

static – contains CSS styling files

requirements.txt – lists required packages (optional)
