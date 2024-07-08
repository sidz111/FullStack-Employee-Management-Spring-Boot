# Employee Management System

This is a simple Employee Management System web application built using Spring Boot, Thymeleaf, and Spring Data JPA. It allows users to perform CRUD operations on employees, including creating, reading, updating, and deleting employee records. The application also supports pagination and sorting of employee records.

## Features

- Add new employees
- Update existing employee details
- Delete employees
- View a list of all employees
- Pagination and sorting of employee records

## Technologies Used

- Java 17
- Spring Boot 2.7.0
- Spring Data JPA
- Thymeleaf
- H2 Database


## Getting Started

### Prerequisites

- JDK 17
- Maven 3.6.0 or higher

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/sidz111/FullStack-Employee-Management-Spring-Boot.git
## Application Endpoints

- **Home Page (List Employees):** `GET /`
- **Add Employee Form:** `GET /showNewEmployeeForm`
- **Save Employee:** `POST /saveEmployee`
- **Update Employee Form:** `GET /showFormForUpdate/{id}`
- **Delete Employee:** `GET /deleteEmployee/{id}`
- **Paginated and Sorted Employees List:** `GET /page/{pageNo}?sortField={fieldName}&sortDir={direction}`

## Usage

### Adding a New Employee

1. Click on "Add New Employee" on the home page.
2. Fill out the form with employee details.
3. Click "Save" to add the new employee to the database.

### Updating an Employee

1. Click on the "Edit" button next to the employee you wish to update.
2. Modify the employee details in the form.
3. Click "Update" to save the changes.

### Deleting an Employee

1. Click on the "Delete" button next to the employee you wish to remove.
2. Confirm the deletion.

### Pagination and Sorting

- Use the pagination controls at the bottom of the employee list to navigate between pages.
- Click on the column headers to sort the list by that column in ascending or descending order.

