# Coding_Challenge_CarRentalSystem

Car Rental System

This coding challenge is a Car Rental System Database designed using MS SQL Server. It aims to manage vehicle leases, customers, payments, and vehicle availability. The database follows a structured relational model to ensure efficient data management for a car rental business.

Key Components:

1 - Vehicle Table:

Stores details of available vehicles, such as make, model, year, daily rental rate, and status (availability).
Columns: vehicleID, make, model, year, dailyRate, status, passengerCapacity, engineCapacity.

2 - Customer Table:

Contains customer information including name, email, and phone number.
Columns: customerID, firstName, lastName, email, phoneNumber.

3 - Lease Table:

Manages lease agreements between customers and vehicles, including lease type (daily/monthly), start date, and end date.
Columns: leaseID, vehicleID, customerID, startDate, endDate, type.

4 - Payment Table:

Keeps track of payments made for each lease, including payment date and amount.
Columns: paymentID, leaseID, paymentDate, amount.
