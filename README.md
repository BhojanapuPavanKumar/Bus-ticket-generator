🚌 Bus Ticket Booking System (C Language)
This is a simple Bus Ticket Booking System developed in C language, allowing users to manage buses and seat reservations efficiently.

The system supports:

Adding new buses

Displaying available buses between routes

Booking and canceling seats

Viewing available and booked seats for a specific bus

🚀 Features
Add New Bus
Add bus details like ID, origin, destination, fare, and total number of seats.

Display Available Buses
View all buses available between the selected origin and destination.

Book a Seat
Book a specific seat number on a selected bus.

Cancel a Seat
Cancel a previously booked seat on a bus.

Display Available Seats
View all the seats that are free for booking on a particular bus.

Display Booked Seats
View all the seats that are already booked on a bus.

🛠️ Technologies Used
Language: C

Libraries: Standard C Libraries (stdio.h, stdlib.h, string.h)
 Project Structure
struct Seat — represents a seat (number, booked status)

struct Bus — represents a bus (ID, route, fare, seat array)

Global Arrays — store multiple buses

Functions — manage buses, seats, booking, cancellations, and displays

 Future Improvements
File handling to save and retrieve bus/booking data permanently.

Admin login and secure access.

Dynamic memory allocation for better scalability.

Online payment simulation for seat booking.
