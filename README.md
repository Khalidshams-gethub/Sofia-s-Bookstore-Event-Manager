project:
  name: "Sofia’s Bookstore Event Manager"
  overview: >
    A Python console application used to manage bookstore events such as book clubs,
    author signings, and sales. The system allows users to create, update, delete,
    and view events, as well as manage attendees.

features:
  - Add new events
  - View all events
  - Update event details
  - Delete events
  - Add attendees
  - Prevent duplicate Event IDs
  - Menu-driven interface
  - Handles invalid input using try/except

technologies:
  - Python 3
  - Lists
  - Dictionaries
  - Functions
  - Loops
  - Exception Handling

data_structure:
  events_list: "List of event dictionaries"
  event_example:
    id: 101
    name: "Author Signing"
    type: "Signing"
    date: "2026-03-10"
    time: "15:00"
    attendees:
      - Alice
      - Bob

menu_options:
  - "1. Add Event"
  - "2. View Events"
  - "3. Update Event"
  - "4. Delete Event"
  - "5. Add Attendee"
  - "6. Exit"

functions:
  - add_event(events_list)
  - view_events(events_list)
  - update_event(events_list)
  - delete_event(events_list)
  - add_attendee(events_list)

how_to_run:
  steps:
    - Install Python 3
    - Clone the repository
    - Run: python event_manager.py

learning_objectives:
  - Use variables and data types
  - Manage data using lists and dictionaries
  - Organize code with functions
  - Implement input validation
  - Build a menu-driven program

author:
  name: "Mohammad Khalid Shams"
  program: "IT / Cybersecurity Student"
  school: "North Seattle College"
