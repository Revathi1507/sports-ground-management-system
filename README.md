# Community Sports Ground Booking System

This project is a **Java console application** developed using **JDBC and MySQL** to manage sports ground bookings for a community or residential association.  
It handles booking registration, slot confirmation, cancellation, and post-usage monitoring.

---

## Key Features

- Register new sports ground bookings
- View bookings by date and status
- Prevent overlapping confirmed bookings
- Record ground usage details after play
- Update usage records with validation
- Generate basic usage reports

---

## Technologies Used

- Java
- JDBC
- MySQL
- DAO Architecture
- Console Application

---

## Database Tables

- `GROUND_SLOT_TBL` – Stores booking information
- `SLOT_USAGE_TBL` – Stores actual usage details after slot completion

---

## How It Works

1. User registers a booking (PENDING)
2. Booking is confirmed after slot validation
3. Ground usage is recorded after play
4. Booking status is marked COMPLETED
5. Reports help analyze ground utilization


Student Project – Java & JDBC  
