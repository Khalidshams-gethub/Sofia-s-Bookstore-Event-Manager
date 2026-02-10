Sofia’s Bookstore Event Manager
Project Overview

Sofia’s Bookstore Event Manager is a Python console application designed to manage bookstore events such as book clubs, author signings, and sales. The system replaces manual tracking with a structured digital solution.

The program allows users to:

Add new events

View existing events

Update event details

Delete events

Add attendees

Features

Menu-driven interface

Unique Event ID validation

Event management (Create, Read, Update, Delete)

Attendee tracking

Input validation with error handling

Clean and readable output

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

ID: 101
Name: Author Signing
Type: Signing
Date: 2026-03-10
Time: 15:00
Attendees: Alice, Bob

Program Menu

When the program runs, users will see:

Add Event

View Events

Update Event

Delete Event

Add Attendee

Exit

The program continues running until Exit is selected.

Functions Included

add_event(events_list)

view_events(events_list)

update_event(events_list)

delete_event(events_list)

add_attendee(events_list)

Each function modifies the shared events list.

How to Run the Program

Install Python 3

Clone the repository

Navigate to the project folder

Run the program using:

python event_manager.py

Learning Objectives

This project demonstrates:

Using variables and data types

Managing data using lists and dictionaries

Organizing code with functions

Input validation and error handling

Menu-driven program design

Author

Mohammad Khalid Shams
IT / Cybersecurity Student
North Seattle College
