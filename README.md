# CODETECH-Task1
NAME: Mohammed Shajith khan F

COMPANY: CODTECH IT SOLUTIONS

ID: CT6WDS1876

DURATION: SEPTEMBER 30TH 2024 TO NOVEMBER 15TH 2024

OVERVIEW OF THE PROJECT PROJECT: HOTEL BOOKING SYSTEM
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

Output:
![4fdbcb25-3bb6-409d-b250-e8d736da8cd0](https://github.com/user-attachments/assets/0062009e-77d3-476f-aa5d-14b516057237)
![ff37f999-c214-40b0-8f5a-8c40e36ff397](https://github.com/user-attachments/assets/8f0cb14b-4114-48af-925f-003320487d9a)
![05016f2f-22e3-41d3-a34a-acc97680bddb](https://github.com/user-attachments/assets/7d8ea9d8-3fc5-4b10-bccc-9c30f4d27ed9)
![4442841d-5267-4c2d-a75a-2c45b3316c4d](https://github.com/user-attachments/assets/68c8b35e-6cab-4337-ae0b-4112bcb3aa75)
![a88f4dd6-7827-4077-bdd3-dbb9983a887a](https://github.com/user-attachments/assets/40235474-4c02-4a86-a733-d41dafb8c5af)
![b24742b3-2b37-423e-add6-39429ea90050](https://github.com/user-attachments/assets/6ae251d1-ddd9-4ede-a5ae-eb584a837545)



TECHNOLOGY USED: MySQL
