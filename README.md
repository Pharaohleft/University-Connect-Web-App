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
<img width="928" height="529" alt="Screenshot 2026-02-02 152219" src="https://github.com/user-attachments/assets/870d2bb8-837f-461e-a5f4-a0ddc332a581" />

---

## Project Objective

The objective of this project is to:
- Digitize student–faculty–admin communication
- Provide a centralized platform for announcements and messaging
- Reduce manual work and improve transparency
- Enable role-based access for Admin, Faculty, and Students
<img width="840" height="820" alt="Screenshot 2026-02-02 152317" src="https://github.com/user-attachments/assets/fae4bb3f-7272-4d6c-a4fe-b3a602d529b8" />

---

## Core Features
<img width="693" height="610" alt="admin" src="https://github.com/user-attachments/assets/9ea22c51-03c9-4ab3-bbfa-9a1547d8c27a" />
<img width="637" height="561" alt="faculty" src="https://github.com/user-attachments/assets/b0ffcfbc-7dbe-4d6b-a0c4-111c7bfe98a5" />
<img width="640" height="519" alt="student" src="https://github.com/user-attachments/assets/c6b6047c-f31f-446d-b755-d1b0db7f78e3" />

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
<img width="896" height="657" alt="built" src="https://github.com/user-attachments/assets/6024fbd4-280c-408f-8636-97467ba0d80d" />


### Sequence Diagrams
- Admin sequence: login → manage users → upload circulars → logout
- Faculty sequence: login → chat → notifications → logout
- Student sequence: login → chat → notifications → logout
<img width="624" height="576" alt="sequence " src="https://github.com/user-attachments/assets/6e780d20-9766-47f0-9fd9-ca7db0b8f799" />
<img width="757" height="713" alt="seq faculty" src="https://github.com/user-attachments/assets/ede4aab2-4d5a-44ca-8be1-370a309b714e" />
<img width="620" height="495" alt="student seq" src="https://github.com/user-attachments/assets/841ea108-6868-4291-9baa-6031559adaba" />

### Development Model
- Waterfall Model
- Project planning supported using a Gantt Chart
<img width="936" height="610" alt="testing" src="https://github.com/user-attachments/assets/c48fddcd-8c95-4164-a445-6c4849eb2ee8" />

### ER Diagram
The ER diagram defines:
- Admin, Faculty, and Student login entities
- Relationships between users, messages, and notifications
- Central database controlling all modules

### Use Case Diagrams
- Admin Use Case
- Faculty Use Case
- Student Use Case


### Activity Diagrams
- Role-based workflows showing login validation and module navigation
<img width="443" height="306" alt="activity 1" src="https://github.com/user-attachments/assets/765df70a-3067-4e7a-a98a-a954f33bd8db" />
<img width="444" height="317" alt="activity 2" src="https://github.com/user-attachments/assets/e6688386-7e3b-4a31-87b1-1f8cae23d7ba" />
<img width="451" height="296" alt="activity 3" src="https://github.com/user-attachments/assets/03761f71-674b-4921-9a2b-fddd29a9fed0" />

### Data Flow Diagrams (DFD)
- Context-level DFD
- Level 1 and Level 2 DFD illustrating data movement between modules and database
<img width="778" height="463" alt="dfd" src="https://github.com/user-attachments/assets/592f1dc6-332e-4aea-8408-6822f5c526ea" />
<img width="604" height="827" alt="dfd prediction" src="https://github.com/user-attachments/assets/c8788dd1-2a97-4f73-af1d-325db2bd0870" />
<img width="469" height="672" alt="db design" src="https://github.com/user-attachments/assets/1d5afd39-97e9-456f-96a6-313e0d74ec12" />

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
<img width="838" height="738" alt="Screenshot 2026-02-02 150931" src="https://github.com/user-attachments/assets/c11abbe7-4cee-4683-a1df-fb506d8eebd2" />

