# CODETECH-Task1
NAME: Mohammed Shajith khan F

COMPANY: CODTECH IT SOLUTIONS

ID: CT6WDS1866

DURATION: SEPTEMBER 30TH 2024 TO NOVEMBER 15TH 2024

MENTOR: NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT PROJECT:HOTEL BOOKING SYSTEM
OBJECTIVES:Create a database for managing hotel bookings, including rooms, customers, reservations, and payments. This project Involves handling complex queries and managing booking data. Design tables for rooms, customers, reservations, and payments.

KEY ACTIVITES:
1.Room Availability Query:
The query checks for room availability by excluding any rooms that overlap with a specified date range, unless the reservation is canceled. This should accurately list available rooms for booking.

2.Reservation Details by Customer:
This query joins reservations and customers to get a specific customer’s reservations, giving a quick way to view past and upcoming reservations for an individual.

3.Monthly Revenue Calculation:
Summing total_price for reservations within a given month (where status is 'Confirmed') provides a good revenue metric. Consider also filtering by check_out_date for more accuracy, as some rooms booked in one month may be checked out in another.

4.Unpaid Reservations:
This query identifies customers with unpaid reservations by joining customers, reservations, and payments, and checking for reservations where the payment is either 'Pending' or absent.
You might consider adjusting LEFT JOIN payments to ensure it captures all cases where p.payment_status is incomplete, such as adding p.payment_status = 'Failed' if necessary.

TECHNOLOGY USED: MySQL
