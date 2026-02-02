# University-Connect-Web-App

# Student Council Android & Web App  
*(College Connect / DBIT Easy Admin)*

A multi-portal system built for **Don Bosco Institute of Technology (DBIT)** to reduce manual coordination and improve communication between **students, faculty, and administrators**.  
The system centralizes student/faculty management, circulars, events, and in-app communication using a shared database and role-based access.

---

## Problem Statement

In the existing system:
- Students had to physically visit faculty or administration for basic queries
- Important notices were displayed only on notice boards
- Event and circular information was scattered across multiple platforms

This resulted in:
- Delays in communication
- Missed announcements
- Increased manual effort for administration

---

## Project Objective

The objective of this project is to:
- Digitize student–faculty–admin communication
- Provide a centralized platform for announcements and messaging
- Reduce manual work and improve transparency
- Enable role-based access for Admin, Faculty, and Students

---

## Core Features

### Admin Portal
- Secure login
- Add / update / delete student records
- Assign students by **year, section, department**
- Add / update / delete faculty records
- Upload **events and circulars**
- Central control over system data

### Faculty Portal
- Secure login
- Access department-level and college-level chat
- View student details
- Receive notifications for messages and updates

### Student Portal
- Secure login
- Access chats based on department, year, and section
- View faculty details
- Receive notifications for messages, events, and circulars

---

## System Design

### Development Model
- Waterfall Model
- Project planning supported using a Gantt Chart

### ER Diagram
The ER diagram defines:
- Admin, Faculty, and Student login entities
- Relationships between users, messages, and notifications
- Central database controlling all modules

### Use Case Diagrams
- Admin Use Case
- Faculty Use Case
- Student Use Case

### Sequence Diagrams
- Admin sequence: login → manage users → upload circulars → logout
- Faculty sequence: login → chat → notifications → logout
- Student sequence: login → chat → notifications → logout

### Activity Diagrams
- Role-based workflows showing login validation and module navigation

### Data Flow Diagrams (DFD)
- Context-level DFD
- Level 1 and Level 2 DFD illustrating data movement between modules and database

---

## Technology Stack

### Android Application
- Java
- Android Studio

### Web Application
- PHP (Laravel) *(as mentioned in feasibility study)*
- Java / ASP.NET *(referenced in conclusion section)*

### Database
- Microsoft SQL Server

---

## System Requirements

### Hardware Requirements
- PC/Laptop: i3 or higher, 1GB RAM, 5GB storage
- Android Device: Quad-core processor, 1GB RAM

### Software Requirements
- Windows 7 or higher
- Java
- Android Studio
- Android OS 5.0 or higher

---

## Recommended Repository Structure

