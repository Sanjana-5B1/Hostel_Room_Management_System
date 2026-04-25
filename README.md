#  Hostel Room Management System

A Java-based desktop application for efficient hostel room allocation and management.  
This system provides a user-friendly GUI to manage students, allocate rooms, and monitor hostel occupancy.

---

##  Features

```
-  Student Registration
-  Multiple Hostel Branch Management
-  Room Allocation (Single / Multi-bed)
-  Search by Roll Number or Name
-  Real-time Hostel Status (Rooms, Beds, Vacancies)
-  Waiting List Handling
-  Interactive GUI using Java Swing
-  Visual Room Grid (Color-coded availability)

---
```

##  Project Structure

Hostel_Room_Management_System/
│
├── src/
│ └── hostel/
│ ├── Student.java
│ ├── Room.java
│ ├── SingleRoom.java
│ ├── MultiRoom.java
│ ├── Hostel.java
│ ├── HostelBranch.java
│ ├── HostelManager.java
│ └── MainUI.java
│
├── README.md
└── .gitignore

 
---

## System Design

### 🔹 Student Management
Each student is uniquely identified using roll number (no duplicates allowed globally).

### 🔹 Room Allocation Logic
- Allocates based on:
  - Room preference (or ANY)
  - Availability
- If no room is available → student is added to waiting list

### 🔹 Hostel Structure
- Multiple hostels supported:
  - Savithri Hostel
  - Samyutha Hostel
  - Saudhamini Hostel

---

## GUI Highlights

- Clean and modern Swing UI
- Room grid visualization:
  -  Green → Empty
  -  Yellow → Partially filled
  -  Red → Full
- Click any room to view occupants

---

##  Technologies Used

- Java (Core + OOP)
- Java Swing (GUI)
- Collections Framework

---

##  How to Run

1. Clone the repository:
```bash
step 1: Clone Repository
git clone https://github.com/Sanjana-5B1/Hostel_Room_Management_System.git
Step 2: Navigate to Source Folder
cd Hostel_Room_Managment_System/src
Step 3: Compile Java Files
javac hostel/*.java
Step 4: Run Application
java hostel.MainUI 
