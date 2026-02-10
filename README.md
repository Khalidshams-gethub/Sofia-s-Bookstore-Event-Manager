Overview

Sofia’s Bookstore Event Manager is a Python console application designed to help manage bookstore events such as book clubs, author signings, and sales.

The program allows users to create, update, delete, and view events, as well as manage event attendees. It replaces the bookstore’s manual paper tracking system with a simple digital solution.

Features

Add new events

View all existing events

Update event details

Delete events

Add attendees to events

Prevent duplicate Event IDs

Handles invalid user input gracefully

Menu-driven interface

Technologies Used

Python 3

Lists

Dictionaries

Functions

Loops

Exception Handling (try/except)

Event Data Structure

Each event is stored as a dictionary inside a list called events_list.

Example:

{
    "id": 101,
    "name": "Author Signing",
    "type": "Signing",
    "date": "2026-03-10",
    "time": "15:00",
    "attendees": ["Alice", "Bob"]
}

Program Menu

When the program runs, users see:

1. Add Event
2. View Events
3. Update Event
4. Delete Event
5. Add Attendee
6. Exit


Users can perform multiple actions until they choose Exit.

Functions

The program includes the following main functions:

add_event(events_list)

view_events(events_list)

update_event(events_list)

delete_event(events_list)

add_attendee(events_list)

All functions modify the shared events_list.

How to Run the Program

Install Python 3 if not already installed.

Download or clone this repository.

git clone <your-repository-link>


Open terminal or command prompt.

Run the program:

python event_manager.py

Learning Objectives

This project demonstrates:

Use of variables and data types

Managing collections using lists and dictionaries

Creating modular programs with functions

Input validation and error handling

Menu-driven program design

Author

Mohammad Khalid Shams
Cybersecurity & IT Student
North Seattle College
