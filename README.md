# CloudExify-Project-3

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

# Employee Management System (EMS)

A Java Swing desktop application for managing employee records through a clean, modern, dark-themed graphical user interface.

## Overview

The **Employee Management System (EMS)** is designed to make common employee-management tasks simple and organized. The application provides separate employee types, employee registration/login, employee record management, searching, updating, reporting, and dashboard functionality.

The project is built using **Java Swing** and follows a package-based structure to keep the GUI, models, and management logic organized.

## Main Features

### Login & Registration

- User registration with a username and password.
- Login using the registered account.
- Account information is stored so the user does not have to register every time.
- Clean login/register interface.

### Employee Management

The system supports three employee types:

- **Manager**
  - Employee ID
  - Name
  - Gender
  - Age
  - Base Salary
  - Manager Bonus

- **Developer**
  - Employee ID
  - Name
  - Gender
  - Age
  - Base Salary
  - Years of Experience

- **HR**
  - Employee ID
  - Name
  - Gender
  - Age
  - Base Salary

### Add Employee

- Add new employee records.
- Employee ID and basic information validation.
- Employee-specific fields appear according to the selected employee type.
- HR only displays the salary field.
- Manager displays the bonus field.
- Developer displays the experience field.
- Employee records are saved through the employee-management layer.

### Update Employee

- Select an existing employee and update their information.
- Employee ID remains protected while editing.
- Employee-specific fields are displayed according to employee type.
- Updated information is reflected on the dashboard.

### Search

- Search employees by **name or employee ID**.
- Multiple employees with the same name can be displayed if they have different IDs.
- Search results show useful information such as:
  - Employee ID
  - Name
  - 
### Reports

- Displays employee records separately.
- Provides a clear overview of employees and their information.
- Employee IDs make individual records distinguishable, even when names are the same.

### Settings

The settings section includes useful application options such as:

- Refresh Dashboard
- About Employee Management System
- Application information

### Logout

- Allows the currently logged-in user to safely return to the login screen.

## User Interface

EMS uses a modern dark-themed interface designed for a clean and professional appearance.

### Design Highlights

- Dark navy/slate backgrounds
- Purple accent colors
- Modern typography
- Styled buttons and input fields
- Clean dashboard layout
- Sidebar navigation
- Dedicated dialogs for adding and updating employees
- Search results presented in a dark-themed interface

## Technologies Used

- **Java**
- **Java Swing**
- **Object-Oriented Programming (OOP)**
- **File Handling**

## Validation

The application validates important employee information before saving.

Examples include:

- Required fields cannot be empty.
- Age must be numeric and greater than zero.
- Salary must be numeric and greater than zero.
- Manager bonus must be numeric when required.
- Developer experience must be numeric when required.
- Employee IDs are used to distinguish employee records.

## How to Run

### Requirements

Make sure you have:

- **JDK 17 or later** recommended
- A Java-compatible IDE such as:
  - IntelliJ IDEA
  - Eclipse
  - NetBeans
  - Visual Studio Code with Java extensions

### Running in an IDE

1. Open the project in your Java IDE.
2. Make sure all source files are inside the correct packages.
3. Make sure the required data files are available in the expected project location.
4. Build/compile the project.
5. Run the application's main class, which launches the login window.

## Project Structure

```text
EmployeeManagementSystem/
│
├── src/
│   ├── gui/
│   │   ├── LoginFrame.java
│   │   ├── Dashboard.java
│   │   ├── AddEmployeeDialog.java
│   │   └── UpdateEmployeeDialog.java
│   │
│   ├── model/
│   │   ├── Employee.java
│   │   ├── Manager.java
│   │   ├── Developer.java
│   │   └── HR.java
│   │
│   ├── manager/
│   │   └── EmployeeManager.java
│   │
│   └── utils/
│       └── FileHandler.java
│
├── Main.java
├── README.md
└── .gitignore

 ```
## Register an account
<img width="887" height="592" alt="a" src="https://github.com/user-attachments/assets/3aac3f89-d72d-4e62-a3ec-99b00db16a8d" />

## Login panel
<img width="481" height="553" alt="b" src="https://github.com/user-attachments/assets/d7a86aa8-8bd5-4457-bcd3-0b658f77765f" />

## Dashboard
<img width="1366" height="729" alt="c" src="https://github.com/user-attachments/assets/045d51e4-c91f-49fe-aea6-1992a6ca3bea" />

## Add Employee form
<img width="585" height="671" alt="f" src="https://github.com/user-attachments/assets/ff5849a1-31df-4184-8a84-5a04cc238816" />

## Update form
<img width="487" height="595" alt="g" src="https://github.com/user-attachments/assets/08fc5210-2efa-48fc-ae43-28fd7bc75410" />

## Search any Employee by name
<img width="707" height="423" alt="h" src="https://github.com/user-attachments/assets/a0ef7114-b8bf-47ca-a551-544465fa7493" />

## All Employee's record
<img width="932" height="535" alt="i" src="https://github.com/user-attachments/assets/5b5c7cbc-db3e-4d39-9040-8d1c3f58b9da" />

## Reports
<img width="1001" height="660" alt="d" src="https://github.com/user-attachments/assets/124a4308-8316-431e-a22a-e505f8cf2f7f" />

# Setting
<img width="499" height="406" alt="e" src="https://github.com/user-attachments/assets/e9f49944-460f-4625-a53d-bd6912f96289" />

## About section
<img width="275" height="222" alt="about" src="https://github.com/user-attachments/assets/9b19d819-068b-478d-9abf-c1e488b19019" />

# BUTTONS
## login
<img width="263" height="124" alt="login" src="https://github.com/user-attachments/assets/99b937ab-dedb-4602-a29e-01331e066e51" />

## Delete
<img width="288" height="121" alt="delete" src="https://github.com/user-attachments/assets/c980a771-e7a1-42b2-88b9-5d48cb7b9061" />

## Refresh
<img width="264" height="118" alt="refresh" src="https://github.com/user-attachments/assets/2e7e249b-e3f0-4149-a64c-b8abc8869d69" />

## Logout
<img width="265" height="125" alt="logout" src="https://github.com/user-attachments/assets/b8bc13e3-8e0d-4669-91de-db75bf1945d5" />
