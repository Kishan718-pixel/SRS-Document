SOFTWARE REQUIREMENTS SPECIFICATION (SRS)

Project Title: Task Manager Application

Document Version: 1.0

Prepared By: Kishan Yadav

Project Type: Software Development Internship

Organization: CodeOrbit Tech

1. Introduction

The Task Manager Application is a simple software application designed to help users manage their daily activities and tasks efficiently.

It allows users to create new tasks, view existing tasks, update task details, mark tasks as completed, and delete tasks when they are no longer required.

The main objective of this application is to improve productivity and help users organize their daily work in an easy and systematic way.


##Purpose

The purpose of the Task Manager Application is to provide users with a simple and efficients platforms to organize and manage thier daily tasks.

This application helps users keep track of thier work, manage thier time, and improve productivity .

The system aims to make task managment easy, organized, and user- friendly.


## 3. Scope

The Task Manager Application will provide the following features:

1. Users can add new tasks.
2. Users can view all available tasks.
3. Users can update existing tasks.
4. Users can delete tasks.
5. Users can mark tasks as completed.
6. Users can organize their daily activities.

### Limitations

1. The application will initially support basic task management.
2. Internet connectivity may be required for future online features.
3. Advanced features like team collaboration are not included in the initial version.


## 4. Project Objectives

The main objectives of the Task Manager Application are:

1. To help users manage their daily tasks.
2. To improve time management and productivity.
3. To provide an easy-to-use interface.
4. To reduce the chances of forgetting important tasks.
5. To allow users to track task completion.
6. To make daily work more organized.


## 5. Overall Description

### 5.1 Product Perspective

The Task Manager Application is a standalone software
application designed to manage daily tasks.

It provides a simple platform where users can create,
view, update, and delete their tasks.


### 5.2 User Classes

The application is designed for the following users:

1. Students – To manage assignments and study schedules.
2. Employees – To organize their daily work.
3. General Users – To manage personal activities.


### 5.3 Operating Environment

The application can operate in the following environment:

1. Operating System: Windows, Linux, or macOS.
2. Platform: Desktop or Web Browser.
3. Programming Language: Python (planned implementation).
4. Code Editor: Visual Studio Code.


### 5.4 Assumptions and Dependencies

1. Users have basic computer knowledge.
2. Users can enter and manage their tasks.
3. The application requires a supported operating environment.
4. Data storage will depend on the implementation.



## 6. Functional Requirements

The Task Manager Application shall provide the following functionalities:

### FR-01: Add New Task
The system shall allow users to create new tasks by entering a task title and description.

### FR-02: View Tasks
The system shall allow users to view all the tasks stored in the application.

### FR-03: Update Task
The system shall allow users to edit and update existing task details.

### FR-04: Delete Task
The system shall allow users to delete tasks that are no longer required.

### FR-05: Mark Task as Completed
The system shall allow users to mark tasks as completed.

### FR-06: Input Validation
The system shall validate user input and prevent empty task entries.



## 7. Non-Functional Requirements

### NFR-01: Performance
The application should respond quickly to user actions and display tasks without unnecessary delay.

### NFR-02: Usability
The application should provide a simple and user-friendly interface that is easy to understand.

### NFR-03: Reliability
The application should perform its functions correctly and maintain accurate task information.

### NFR-04: Security
The application should protect stored task information from unauthorized access.

### NFR-05: Maintainability
The application code should be well-organized and easy to modify or update.

### NFR-06: Compatibility
The application should work properly in its supported operating environment.


## 8. Use Cases

### Use Case 1: Add Task

**Actor:** User

**Precondition:** The application must be running.

**Steps:**
1. User opens the application.
2. User selects the Add Task option.
3. User enters the task title and description.
4. User submits the task.
5. The system saves the task.

**Expected Result:** A new task is successfully added.

### Use Case 2: View Tasks

**Actor:** User

**Steps:**
1. User opens the application.
2. User selects the View Tasks option.
3. The system displays all available tasks.

**Expected Result:** All saved tasks are displayed.

### Use Case 3: Update Task

**Actor:** User

**Steps:**
1. User selects an existing task.
2. User chooses the Update option.
3. User modifies the task details.
4. User saves the changes.

**Expected Result:** The task is successfully updated.

### Use Case 4: Delete Task

**Actor:** User

**Steps:**
1. User selects an existing task.
2. User chooses the Delete option.
3. The system removes the selected task.

**Expected Result:** The task is deleted successfully.

### Use Case 5: Complete Task

**Actor:** User

**Steps:**
1. User selects a pending task.
2. User chooses the Mark as Completed option.
3. The system updates the task status.

**Expected Result:** The task status changes to Completed.



## 9. User Stories

1. As a student, I want to add tasks so that I can remember my assignments.

2. As a user, I want to view all my tasks so that I can track my daily activities.

3. As a user, I want to update tasks so that I can modify incorrect information.

4. As a user, I want to delete tasks so that I can remove unnecessary tasks.

5. As a user, I want to mark tasks as completed so that I can track my progress.



## 10. Conclusion

The Task Manager Application will provide a simple and effective solution for managing daily tasks.

This SRS document describes the functional and non-functional requirements, use cases, and user stories of the application.

The document will help developers understand the system requirements and guide the development process.
