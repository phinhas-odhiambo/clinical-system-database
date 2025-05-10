#  Clinic Booking System Database

##  Project Description

This project implements a **Clinic Booking System** using **MySQL**. It is designed to manage clinic appointments by storing data about patients, doctors, their specializations, and scheduled appointments. The system supports relationships such as:

- One-to-Many between Patients and Appointments
- One-to-Many between Doctors and Appointments
- Many-to-Many between Doctors and Specializations

All tables are created with appropriate constraints to ensure data integrity (e.g., primary keys, foreign keys, NOT NULL, UNIQUE, ENUM types).

---

##  How to Set Up and Run

### Prerequisites

- MySQL Server (e.g., MySQL 8.x)
- MySQL client (CLI or GUI like MySQL Workbench, DBeaver, or phpMyAdmin)

### Steps

1. **Clone or Download this Repository**

   ```bash
   git clone https://github.com/phinhas-odhiambo/clinic-booking-system-db.git
   cd clinic-booking-system-db
