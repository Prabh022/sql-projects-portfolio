# Smart Rental Management System (SRMS)

Smart Rental Management System (SRMS) is an Oracle SQL database project that manages tenants, rental units, leases, payments, maintenance requests, and staff assignments.

It is designed to show practical skills in:
- Database design and normalization
- ER modeling
- SQL querying (joins, aggregates, subqueries)
- Stored procedures
- Triggers
- Views
- Constraints and indexing

## Features

- Tenant and unit management
- Lease tracking
- Monthly rent payments
- Maintenance requests and staff assignments
- Views for quick reporting
- Example advanced queries

## Tech Stack

- Oracle Database
- Oracle SQL (PL/SQL for procedures and triggers)
- SQL Developer / Oracle LiveSQL

## Project Structure

```text
/SmartRentalManagementSystem
│
├── README.md
│
├── sql/
│   ├── schema.sql
│   ├── sample_data.sql
│   ├── queries.sql
│   ├── procedures.sql
│   ├── triggers.sql
│   ├── views.sql

## How to Run

Follow these steps to set up and run the project in **Oracle SQL Developer** or **Oracle LiveSQL**.

### 1. Open SQL Developer or LiveSQL

Log in to your Oracle database environment.

### 2. Run the Database Schema

Execute the following file:

```sql
sql/schema.sql
````

This creates:

* All tables
* All sequences
* All constraints
* All indexes

### 3. Insert Sample Data

Execute the following file:

```sql
sql/sample_data.sql
```

This loads example:

* Tenants
* Units
* Leases
* Payments
* Staff
* Maintenance requests

### 4. Create Views

Execute the following file:

```sql
sql/views.sql
```

This creates the database views used by the project.

### 5. Create Stored Procedures

Execute the following file:

```sql
sql/procedures.sql
```

This creates the stored procedures used by the project.

### 6. Create Triggers

Execute the following file:

```sql
sql/triggers.sql
```

This creates the database triggers used by the project.

### 7. Run Example Queries

Execute the following file:

```sql
sql/queries.sql
```

This file contains **10+ useful and advanced SQL queries** to test and demonstrate the functionality of the database system.

```
```

