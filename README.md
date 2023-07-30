# Railways-Reservation-System-with-Locking-Mechanisms
Developed a Railways Reservation System to manage concurrent access to the reservation database. Implemented locking mechanisms to handle multiple processes simultaneously accessing the database for reservation status checks and bookings.

# Project: Railways Reservation System with Locking Mechanisms
CS69011: Computing Lab 1 

- Developed a Railways Reservation System to manage concurrent access to the reservation database.
- Implemented locking mechanisms to handle multiple processes simultaneously accessing the database for reservation status checks and bookings.
- Defined two types of processes: Readers (for status checks) and Writers (for making reservations).
- Utilized read locks for Readers and write locks for Writers, ensuring exclusive access when required.
- Implemented functions for acquiring and releasing read and write locks for each train.
- Created a system with 4 child processes (P1, P2, P3, P4), reading instructions from respective input files (in1, in2, in3, in4).
- Processed reservation and cancellation requests, checking availability using read locks and obtaining write locks for successful reservations.
- Waitlisted passengers were handled appropriately, and cancellations resulted in confirming the first waitlisted passenger.
- Ensured non-preemptive locking and prioritized Writers over new Readers during critical sections.
- Demonstrated proper synchronization and locking techniques for shared memory-based reservation database.
- Simulated the reservation system with 3 trains, each having 10 berths of 2AC, 3AC, and SC classes.

  
