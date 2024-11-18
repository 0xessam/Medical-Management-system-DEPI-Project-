# Medical Management System - DEPI 2024 (Phase 1)

## Introduction

The **Medical Management System** is designed to streamline and enhance hospital operations by providing functionalities for managing patients, doctors, appointments, billing, medical records, and more. This document serves as a guide for setting up and understanding the project's Phase 1 implementation.

## Features (Phase 1)

- **Patient Management**: Store and retrieve patient information.
- **Doctor Management**: Manage doctor profiles and schedules.
- **Appointment Scheduling**: Create, view, and manage appointments.
- **Medical Records**: Store and manage patient medical history.
- **Billing System**: Generate and track bills for services rendered.
- **Department Management**: Manage hospital departments.
- **Medication Management**: Manage the inventory and distribution of medications.
- **Nurse Management**: Manage nurse profiles and assignments.
- **Feedback System**: Collect feedback from patients.
- **Service Management**: Manage hospital services offered.
- **Insurance Providers**: Track patient insurance details and associated providers.

## Project Structure

### 1. **DbContextLayer**
Contains the `HospitalContext` class, which manages the database connections and entity configurations.

### 2. **Interfaces**
Defines generic and specific repository interfaces to ensure consistency and separation of concerns.

### 3. **Repository**
Implements repository classes to handle data operations for each entity, ensuring clean and maintainable data access logic.

### 4. **Models**
Contains entity classes such as `Patient`, `Doctor`, `Appointment`, etc., representing the database tables.

## Setting Up the Project

1. **Clone the Repository**

   Clone this repository to your local machine:

   ```bash
   git clone <repository_url>
