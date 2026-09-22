# Redis Clinic Scheduling Project

## About This Project

I completed this project for CS 650: Advanced Databases at Old Dominion University. The assignment gave me hands on experience working with Redis and using different Redis data structures to build a clinic appointment scheduling system.

The system included patients, doctors, appointments, scheduling, temporary appointment holds, and booking activity.

## Tools I Used

- Redis
- Python
- redis-py
- Google Colab
- Jupyter Notebook

## What I Did

I used Redis hashes to store information about patients, doctors, and appointments. I also worked with sets and sorted sets to organize and retrieve data in different ways.

Some of the main parts of the project included:

- Creating and managing patient, doctor, and appointment data
- Using Redis hashes to store records
- Creating secondary indexes with sets
- Using sorted sets to manage appointment schedules
- Using TTL expiration for temporary appointment holds
- Building a booking process that prevents the same appointment from being booked twice
- Working with WATCH, MULTI, and EXEC for transactions
- Using optimistic locking to handle changes during the booking process
- Using Redis Streams to keep a record of booking activity
- Connecting Python to Redis with redis-py

## What I Learned

Before this project, most of my database experience focused on traditional relational databases and SQL. This assignment helped me understand how a NoSQL database like Redis stores and manages data differently.

I also got more experience with transactions, expiration times, indexing, and handling situations where multiple users could try to access or change the same data. Building the appointment booking portion helped me see how Redis can be used for real applications where speed and data consistency are important.
