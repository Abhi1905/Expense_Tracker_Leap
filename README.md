# Expense Tracker Application

## Overview
This Expense Tracker application is designed to help individuals and groups manage their expenses seamlessly. The application includes features for individual expense tracking as well as group expense management.

### Technologies Used
#### Backend (Java/Spring Boot)
- Spring Boot
- Spring MVC
- Spring Data JPA
- MySQL (or PostgreSQL) for data storage
- Error handling and validation implemented

#### Frontend (ReactJS)
- React for building user interfaces
- HTML/CSS/JavaScript
- Axios for asynchronous requests

### Features

#### Backend
1. **Spring Boot Project Setup:**
   - A Spring Boot project is set up to serve as the backend.

2. **Expense Data Model:**
   - Designed a data model for expenses with attributes like amount, category, date, and description.

3. **RESTful API Endpoints:**
   - Implemented RESTful API endpoints using Spring MVC for CRUD operations on expenses.

4. **Database Integration:**
   - Utilized a relational database (MySQL or PostgreSQL) for storing expense data with Spring Data JPA.

5. **Error Handling and Validation:**
   - Implemented error handling and validation for expense-related operations.

6. **Group Management:**
   - Extended the backend to support group creation, addition/removal of members, and shared expenses within a group.

#### Frontend
1. **Project Setup:**
   - Set up a React project using the specified tools.

2. **Components:**
   - Created components for:
     - Expense list display for individual users.
     - Expense creation form for both individual and group expenses.
     - Expense category-wise analysis for both individual and group expenses.
     - Group creation and management interface.

3. **Integration:**
   - Connected the frontend and Spring Boot backend to enable seamless communication.
   - Utilized asynchronous requests (Axios) to make API calls from the frontend.

4. **Extras (Optional):**
   - Implemented user authentication for personalized expense tracking.
   - Added chart visualization for expense distribution by category for both individual and group views.
   - Incorporated a monthly budget tracker with alerts for exceeding budget limits.
   - Enabled exporting/importing of expense data.



Thank you for considering this Expense Tracker application. Any feedback is welcome!
