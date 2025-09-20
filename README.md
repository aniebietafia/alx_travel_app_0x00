# ALX Travel App
This is a simple travel application built using React Native. The app allows users to explore various travel destinations, view details about each destination, and manage their favorite places.

## Outcomes
* Define models such as Listing, Booking, and Review with correct relationships (e.g., ForeignKey, OneToMany).
* Use Django REST Framework (DRF) serializers to prepare model data for APIs.
* Write and execute a seeding script to insert realistic sample data into the database.
* Apply database seeding to streamline development and testing workflows.

## Key Concepts
* Django Models – Mapping Python classes to database tables.
* Relationships – Implementing one-to-many and many-to-one associations between models.
* Constraints – Ensuring data integrity with validation rules.
* Serializers – Converting complex data types into JSON for APIs using DRF.
* Management Commands – Extending Django’s CLI to perform custom tasks.
* Database Seeding – Populating databases with sample or default data.

## Tasks
Define the database models, create serializers for API data representation, and implement a management command to seed the database.

### Instructions
* Create Models:

    - In listings/models.py, define Listing, Booking, and Review models based on the provided structure.
    - Each model should have appropriate fields, relationships, and constraints.
* Set Up Serializers:

  * Create serializers in listings/serializers.py for Listing and Booking models.
* Implement Seeders:

  * Create a management command in listings/management/commands/seed.py to populate the database with sample listings data.
* Run Seed Command:

    * Test the seeder by running the command to populate the database with sample data.
