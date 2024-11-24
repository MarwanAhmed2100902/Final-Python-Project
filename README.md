# Employee Data Management System

## Project Overview
The **Employee Data Management System** is a Python-based application designed to manage employee records for organizations efficiently. This system provides essential operations to handle employee data with persistent storage using CSV files.

## Features
- **Add Employee**: Enter details like ID, Name, Position, Salary, and Email, and save to a CSV file.
- **Update Employee**: Modify specific employee fields while preserving others.
- **Delete Employee**: Remove employee data by unique ID and update the CSV file.
- **Search Employee**: Retrieve an employee's details using their ID.
- **List All Employees**: Display a comprehensive list of all employees.
- **File Handling**: Data is stored and retrieved from a CSV file for persistent storage.

## Project Structure
1. **Employee Class**: Represents individual employee records.
2. **EmployeeManager Class**: Manages CRUD operations and interacts with the CSV file.
3. **CLI Interface**: A menu-driven command-line interface for user interaction.

## How It Works
1. **Launch Program**: Displays a menu with options (Add, Update, Delete, Search, List, Exit).
2. **Perform Actions**: Select a menu option to execute the desired operation.
3. **Data Persistence**: Changes are automatically saved to a CSV file and reloaded on startup.


