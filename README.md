 README: Hotel Management Database Schema

This SQL script is designed for a comprehensive Hotel Management System. It includes all necessary `DROP` statements to reset the database by removing existing tables and triggers. 
After that, it recreates all essential tables such as `Customer`, `Room`, `Booking`, `Payment`, `Food`, `Staff`, and more, each with relevant fields and foreign key constraints to maintain relational integrity.
The system supports room booking, food ordering, staff management, payments, cancellations, and customer feedback. It also defines six important triggers to enforce business logic—such as preventing double bookings,
managing food stock, auto-confirming bookings upon payment, and calculating refund amounts upon cancellation.This schema is ideal for hotel administrators and developers who are looking to implement a robust and scalable back-end system for hotel operations.
The script should be run in an Oracle SQL environment to initialize or reset the hotel database cleanly and efficiently.
