
README FILE

PARKING – VEHICLE ENTRY & EXIT

---

1. Problem Statement

Problem Statement No.: 09

Title: Parking – Vehicle Entry & Exit

The Parking – Vehicle Entry & Exit system is designed to manage vehicles entering and leaving a parking area. The system maintains vehicle details, parking slot information, vehicle type, entry and exit records, and calculates the parking fee.

---

2. Feature Set

Feature Set: 03

The system includes the following features:

1. Vehicle Details
2. Parking Slot
3. Vehicle Type
4. Vehicle Entry / Exit
5. Fee Calculation

---

3. Student Details

- Name: Sneha Mahipati
- Roll Number: U15CTCZ26S0057
- Class: BCA 1st Year ‘B’

---

4. Course Details

- Enrolment
- Payment
- Enrolment Status

---

5. Project Objective

The main objective of this project is to develop a simple parking management system that can:

- Store vehicle details.
- Identify the type of vehicle.
- Assign an available parking slot.
- Record vehicle entry details.
- Record vehicle exit details.
- Calculate the parking fee.
- Maintain parking records in an organized manner.

---

6. Requirements

Hardware Requirements

- Computer or Laptop
- Keyboard
- Mouse
- Minimum 4 GB RAM
- Storage space for project files

Software Requirements

- Operating System: Windows / Linux
- C Compiler / IDE
- DBMS, if database implementation is used
- Code Editor

---

7. Vehicle Details

The system stores basic information about each vehicle.

Vehicle Attributes

- Vehicle ID
- Vehicle Number
- Owner Name
- Vehicle Type

---

8. Parking Slot

The system maintains information about parking slots.

Parking Slot Attributes

- Slot ID
- Slot Number
- Slot Type
- Slot Status

The slot status can be:

- Available
- Occupied

---

9. Vehicle Type

The system identifies the type of vehicle entering the parking area.

Examples:

- Two-Wheeler
- Car
- Other Vehicle

---

10. Entry and Exit

The system records the entry and exit of vehicles.

Entry Information

- Vehicle ID
- Vehicle Number
- Parking Slot
- Entry Date
- Entry Time

Exit Information

- Vehicle ID
- Parking Slot
- Exit Date
- Exit Time
- Parking Duration
- Parking Fee

---

11. Fee Calculation

The parking fee is calculated based on the parking duration and vehicle type.

Basic Formula

Parking Fee = Parking Duration × Applicable Rate

The applicable rate can be defined according to the vehicle type and parking rules.

---

12. Algorithm

Parking – Vehicle Entry & Exit

Step 1: Start.

Step 2: Enter vehicle details such as Vehicle ID, Vehicle Number, and Owner Name.

Step 3: Select the vehicle type.

Step 4: Check whether a parking slot is available.

Step 5: If a slot is available, assign the parking slot to the vehicle.

Step 6: Record the vehicle entry date and time.

Step 7: Store the vehicle and parking details.

Step 8: When the vehicle exits, enter or record the exit date and time.

Step 9: Calculate the total parking duration.

Step 10: Calculate the parking fee according to the applicable parking rate.

Step 11: Display the parking fee.

Step 12: Update the parking slot status to Available.

Step 13: Store the exit details.

Step 14: Stop.

---

13. Flowchart

The flowchart should represent the following sequence:

START

↓

Enter Vehicle Details

↓

Select Vehicle Type

↓

Check Parking Slot Availability

↓

Is Slot Available?

- No → Display "Parking Slot Not Available" → Stop
- Yes → Assign Parking Slot

↓

Record Entry Date & Time

↓

Store Parking Details

↓

Vehicle Exit

↓

Record Exit Date & Time

↓

Calculate Parking Duration

↓

Calculate Parking Fee

↓

Display Fee

↓

Update Slot Status to Available

↓

Store Exit Details

↓

STOP

---

14. ER Diagram

The ER diagram should contain the following main entities:

VEHICLE

Attributes:

- Vehicle_ID (PK)
- Vehicle_Number
- Owner_Name
- Vehicle_Type

PARKING_SLOT

Attributes:

- Slot_ID (PK)
- Slot_Number
- Slot_Type
- Slot_Status

PARKING_RECORD

Attributes:

- Record_ID (PK)
- Vehicle_ID (FK)
- Slot_ID (FK)
- Entry_Date_Time
- Exit_Date_Time
- Parking_Duration
- Parking_Fee

Relationships

- A Vehicle is assigned to a Parking Slot.
- A Vehicle has a Parking Record.
- A Parking Slot can be used for multiple parking records over time.
- A Parking Record stores the vehicle's entry, exit, duration, and fee details.

---

15. ER Diagram Structure

        ┌──────────────────────┐
        │       VEHICLE        │
        ├──────────────────────┤
        │ Vehicle_ID (PK)      │
        │ Vehicle_Number       │
        │ Owner_Name           │
        │ Vehicle_Type         │
        └──────────┬───────────┘
                   │
                   │
                   │
        ┌──────────▼───────────┐
        │   PARKING_RECORD     │
        ├──────────────────────┤
        │ Record_ID (PK)       │
        │ Vehicle_ID (FK)      │
        │ Slot_ID (FK)         │
        │ Entry_Date_Time      │
        │ Exit_Date_Time       │
        │ Parking_Duration     │
        │ Parking_Fee          │
        └──────────┬───────────┘
                   │
                   │
        ┌──────────▼───────────┐
        │    PARKING_SLOT      │
        ├──────────────────────┤
        │ Slot_ID (PK)         │
        │ Slot_Number          │
        │ Slot_Type            │
        │ Slot_Status          │
        └──────────────────────┘

---

16. Input

The system accepts:

- Vehicle ID
- Vehicle Number
- Owner Name
- Vehicle Type
- Parking Slot
- Entry Date and Time
- Exit Date and Time

---

17. Output

The system displays:

- Vehicle details
- Assigned parking slot
- Vehicle entry details
- Vehicle exit details
- Parking duration
- Total parking fee
- Parking slot availability

---

18. Expected Outcome

The system provides an organized method for managing vehicle parking. It records vehicle entry and exit information, manages parking slots, identifies vehicle types, and calculates the applicable parking fee.

---

19. Conclusion

The Parking – Vehicle Entry & Exit project is a simple and useful system for managing parking activities. It combines vehicle details, parking slots, vehicle types, entry and exit records, and fee calculation into one organized system.

This project is suitable for a BCA 1st Year practical project and demonstrates the basic concepts of algorithm design, flowcharts, ER diagrams, and database management.

---

20. Project Information

Details| Information
Problem Statement| 09
Project| Parking – Vehicle Entry & Exit
Feature Set| 03
Student| Sneha Mahipati
Roll Number| U15CTCZ26S0057
Class| BCA 1st Year ‘B’
Course Details| Enrolment, Payment, Enrolment Status
Main Features| Vehicle Details, Parking Slot, Vehicle Type, Entry/Exit, Fee Calculation
