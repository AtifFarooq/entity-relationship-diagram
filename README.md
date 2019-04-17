# entity-relationship-diagram
An Enhanced Entity Relationship diagram (EERD) for a database application. Based on specifications given by AUER, a newly established (hypothetical) transportation network company in Australia.

# Project Specifications

• Each AUER staff member has a unique StaffID.

• Some AUER staff members are in the process of contracting thousands of drivers and would like to store their data
in the database. Each driver must have a valid driving licence and have access to at least one car that will be used
for rides. Two drivers cannot have access to the same car. Information on drivers includes name, driving licence
number, address and phone number. Information of a car includes its registration number, model and capacity.

• An AUER staff member will help customers to sign up using their unique credit card numbers. A customer can be
either an individual or a business organisation. Individuals should provide their names and phone numbers while
each business organisation should have an address and an ABN (Australian Business Number).

• A ride is booked by one customer only and uses exactly one car. Once a ride is completed, customer’s credit card
would automatically be charged by AUER. The database should store detailed information about about each ride,
including a unique receipt number, the fare, the start time and end time, the origin and the destination.

• To ensure the safety and comfort of the passengers, some AUER staff members must conduct periodic inspections
of all cars. Each inspection result includes the inspection status and inspection date provided by one or more AUER
staff members. The inspection status must be one of three possible options (i.e., perfect, functional and flawed).

# Enhanced Entity Relationship Diagram (EERD)


![alt text](https://raw.githubusercontent.com/AtifFarooq/entity-relationship-diagram/master/EERD_Database.jpg)
