# Backend-Mern-Flow-CampusPlacements
Sample Workflow
Admin
   │
   ▼
Create Event
   │
   ▼
Seats = 100
   │
   ▼
User Books 4 Seats
   │
   ▼
Available Seats = 96
   │
   ▼
Another User Books 10 Seats
   │
   ▼
Available Seats = 86
   │
   ▼
User Cancels Booking
   │
   ▼
Seats Restored
   │
   ▼
Available Seats = 90

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 



Where can this project be used?

This Event Seat Reservation System is a generic booking platform that can be adapted for college events,
conferences, workshops, movie theatres, hospitals, flight and bus reservations, stadium ticketing, webinars, and appointment scheduling.
The core business logic remains the same—managing limited seat inventory, preventing overbooking, handling cancellations, and providing real-time availability through REST APIs.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 


System Use Cases ?
The backend automatically:

Validate data
Prevent overbooking
Update available seats
Generate booking ID
Return JSON response
Handle exceptions
Store booking history

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 

Functional Requirements?

Event Module?

Create Event
Update Event
Delete Event
List Events
Get Event Details


Booking Module?

Book Seat
Cancel Booking
View Booking
View All Bookings


Validation?

Event must exist
Seat count > 0
Email format valid
Cannot book more seats than available
Business Rules
Seats cannot become negative.
Booking is allowed only if enough seats are available.
Cancelling a booking restores the reserved seats.
An event cannot have more bookings than its total capacity.
A booking cannot be made for a deleted event.
All API responses must be returned in JSON format.
Invalid requests must return the appropriate HTTP status code.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project Use Cases

Sample Workflow
Admin
   │
   ▼
Create Event
   │
   ▼
Seats = 100
   │
   ▼
User Books 4 Seats
   │
   ▼
Available Seats = 96
   │
   ▼
Another User Books 10 Seats
   │
   ▼
Available Seats = 86
   │
   ▼
User Cancels Booking
   │
   ▼
Seats Restored
   │
   ▼
Available Seats = 90
 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
 
