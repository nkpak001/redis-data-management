# Redis Data Management & Performance

## Project Overview

This project explores advanced Redis data modeling and performance concepts using a healthcare appointment system. I used Redis to model patients, doctors, and appointments while implementing indexing, scheduling, temporary holds, transaction control, and activity logging.

This project was completed as part of my graduate coursework in Computer Science at Old Dominion University.

## Tools & Technologies

- Redis
- Python
- redis-py
- Google Colab
- Jupyter Notebook

## Project Design

The project models a clinic scheduling system containing:

- Patients
- Doctors
- Appointments
- Doctor specialties
- Appointment schedules
- Temporary appointment holds
- Booking activity records

Redis hashes were used to represent entities, while sets and sorted sets supported indexing and scheduling.

## Technical Work

The project included:

- Modeling data with Redis hashes
- Creating secondary indexes using sets
- Using sorted sets for appointment scheduling
- Implementing time-bound appointment holds with TTL expiration
- Building an atomic booking process to prevent double-booking
- Using WATCH, MULTI, and EXEC for optimistic locking and transaction control
- Handling potential race conditions during concurrent booking attempts
- Using Redis Streams to maintain an audit trail of booking activity
- Applying consistent key naming and namespace conventions
- Working with Python and redis-py to interact with Redis

## Skills Demonstrated

- Redis
- Python
- NoSQL Data Modeling
- Data Structures
- Secondary Indexing
- Transactions
- Optimistic Locking
- TTL and Expiration
- Redis Streams
- Concurrency Control
- Data Validation
- Analytical Problem Solving

## Author

Necey Kpakio  
M.S. Computer Science  
Old Dominion University
