# C++ Phone Record Management System

This project is a C++ console application for managing phone call records.

It allows the user to enter phone records, validate the input, classify users as regular or VIP, sort the records, and export the results into data files.

---

## Features

- input of phone call records
- validation of first name and last name
- phone number format validation
- call duration validation
- support for regular and VIP users
- sorting by surname, name, and phone number
- call cost calculation for regular users
- file export to `.dat` files

---

## Data Model

Each record contains:

- first name
- last name
- phone number
- call duration
- user type (regular or VIP)

VIP users are treated differently in the billing logic, where their price is marked as unlimited.

---

## Technologies Used

- C++
- structs
- functions
- file handling
- string/character array processing

---

## Files Generated

The program generates:

- `SE.dat` – stores entered records
- `sort.dat` – stores sorted records with billing information

---

## Learning Goals

This project demonstrates:

- structured programming in C++
- input validation
- sorting algorithms
- file operations
- business rule implementation
