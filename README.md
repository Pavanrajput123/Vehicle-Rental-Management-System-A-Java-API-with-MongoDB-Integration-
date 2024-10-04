The project involves developing a Java API to interact with a MongoDB database for managing a vehicle rental business. The main goal is to model the various entities (such as vehicles, clients, and administrators) and define their relationships and interactions within the system.

Key Concepts:
Entity Modeling:
Vehicles: Attributes like make, model, year, rental price, and availability.
Clients: Details such as name, contact information, rental history, and payment details.
Administrators: Users who manage the fleet, track rentals, and handle client queries.
Interactions:
Vehicle Rental Process: Clients should be able to browse available vehicles, book rentals, and make payments.
Vehicle Management: Administrators need to manage vehicle availability, update information, and track maintenance.
Client Management: Maintain client profiles, track rental history, and handle client feedback.
Approach:
API Design: The API should expose endpoints for creating, reading, updating, and deleting (CRUD) operations on vehicles, clients, and rentals.
Database Design: MongoDB collections will represent the different entities, utilizing its flexible schema to store complex relationships like rental history or vehicle maintenance.
Business Logic: Implement validation rules (e.g., vehicle availability checks) and other constraints within the API.
