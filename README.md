# Veterinary Clinic Database System

## Overview
Relational database system built using Microsoft Access to manage veterinary clinic operations, including pets, owners, staff, treatments, and equipment while ensuring data integrity.

## Features
- Manage pet and owner information
- Track treatments assigned to pets
- Assign staff to treatments (many-to-many)
- Allocate equipment for treatments
- Structured relational data model

## Database Structure

### Entities
- Owner – Stores owner details
- Pet – Linked to owners
- Treatment – Records treatments for pets
- Staff – Clinic staff information
- Equipment – Equipment used in treatments

### Relationships
- One-to-many: Owner → Pet  
- One-to-many: Pet → Treatment  
- Many-to-many:
  - Treatment ↔ Staff (via TreatmentStaff)
  - Treatment ↔ Equipment (via TreatmentEquipment)

## Technologies Used
- Microsoft Access
- Relational Database Design
- Data Normalization

## Project Purpose
Developed as part of a database design assignment to demonstrate understanding of relational databases, normalization, and entity relationships.

## Future Improvements
- Add advanced queries for reporting
- Improve validation and automation
- Integrate a front-end interface

## Author
Thisama Rupasinghe
