# Mathematical-Modelling-Assignments
Hospital Database Modeling: Subtype/Supertype Relationships in RVH
This project focuses on modeling a database for the Royal Victoria Hospital (RVH) using subtype/supertype relationships. We aim to structure the database in a way that captures the unique roles and shared attributes among different entities like employees and patients.

## Table of Contents
About
Entity Types
Attribute Types
Key Concepts
Methodology
Implications

## About
The project starts by introducing the concept of subtype/supertype relationships. These relationships are crucial for modeling entities that share some common characteristics while possessing unique attributes. The setting for these relationships is the healthcare environment of RVH.

## Entity Types
Employees: A general category that encompasses different roles within the hospital.
Physicians: A subtype of employees, with additional attributes like specialty.
Patients: An entity type with attributes such as health conditions.

## Attribute Types
Shared Attributes: These are attributes common to multiple entity types. For example, both employees and patients may have a name and ID.
Unique Attributes: These attributes are unique to a particular subtype. For instance, specialty is unique to physicians.

## Key Concepts
Inheritance: Subtypes inherit attributes and relationships from their supertype.
Normalization: The structure aims for database normalization to minimize redundancy and dependency.

## Methodology
Design Approach: The project adopts a structured approach to database design, focusing initially on defining entity types and then establishing relationships.
Logical Modeling: The aim is to create a logical model that can be implemented in a physical database.
Implications
Efficiency: A well-designed model allows the hospital to manage its data more efficiently.
Data Integrity: The model ensures that the data is accurate and consistent.
