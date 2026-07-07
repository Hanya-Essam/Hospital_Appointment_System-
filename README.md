# Hospital Appointment System

A C++ console application that manages hospital appointments using a custom built **Binary Search Tree (BST)**, with appointments organized by priority level to support efficient scheduling, searching, and cancellation.

## Authors
- Hanya Essam Eldin Moahmed (Hanya-Essam)
- Habiba Amr Mohamed (habibasaker)

## Features
- Schedule a new appointment (patient name, priority level, and department)
- Display all appointments in order of priority
- Search for appointments by priority level
- Cancel an existing appointment by priority level
- Display all appointments more urgent than a given priority level
- Display all appointments less urgent than a given priority level
- Automatically load an initial set of appointments from an `input.txt` file when the program starts

## How It Works
Each appointment is represented as a node within the BST, where the **priority level** serves as the key used to organize the tree. Appointments with lower priority values are placed to the left of a node, while those with higher values are placed to the right. This structure allows the system to efficiently traverse, search, and manage appointments based on urgency, rather than relying on a simple sequential list.

## Input File Format
The `input.txt` file allows the program to preload a set of appointments automatically when it runs. The file must follow this structure:
```
<number of appointments>
<patient name>
<priority level>
<department>
...
```
