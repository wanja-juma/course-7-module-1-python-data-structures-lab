# Student Data Management System

## Overview
This project is a Python-based Student Data Management System that demonstrates efficient use of core data structures such as lists, tuples, and sets. It also applies functional programming concepts like list comprehensions, set comprehensions, and generator expressions to process and manage student records effectively.

The system allows users to store, filter, and analyze student data in a structured and efficient way.

---

## Features

### 1. Student Data Storage
- Student records are stored as **tuples** inside a list.
- Each student contains:
  - ID
  - Name
  - Major

Example:

(101, "Alice Johnson", "Computer Science")

### 2. Display Student data

Formats and displays student information in a readable format.

### 3. Filter Students by Major

Uses list comprehensions to filter students based on their major.

Example:

Input: "Mathematics"
Output: Only students enrolled in Mathematics

### 4. Track Unique Majors

Uses set comprehension to extract unique majors.
Ensures no duplicate values.

### 5. Efficient Data Processing (Generator)

Uses generator expressions to process large datasets efficiently.
Returns one student at a time instead of storing everything in memory.

## Setup Instructions

1. Prerequisites

Ensure you have the following installed:

Python 3.8 or higher

Check Python version:

-python --version

2. Download the Project

Clone or download the project folder:

-git clone git@github.com:wanja-juma/course-7-module-1-python-data-structures-lab.git

3. Navigate to Project Directory

-cd StudentDataManagement

4. Run the Application

Run the main file:

-python main.py

## Usage Instructions

### When the program runs:

1. Display All Students

The system prints all student records in a formatted structure.

2. Filter Students

You can filter students by major using predefined functions.

Example:

Computer Science students only
Mathematics students only

3. View Unique Majors

The system displays all unique majors using set operations.

4. Generator-Based Processing

The system can iterate through student records efficiently using generators, useful for large datasets.

### Concepts Used

Lists
Tuples
Sets
List Comprehensions
Set Comprehensions
Generator Expressions
Modular