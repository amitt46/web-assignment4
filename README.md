# College Management Web Application

This project is a **Node.js**-based web application designed to facilitate the management of student and course data for a college. It provides an intuitive interface for college administrators to perform CRUD (Create, Read, Update, Delete) operations on student and course records. The application leverages **Express.js** for server-side functionality and **Handlebars.js** as the templating engine for dynamic content rendering.

## Features

- **List and View Records**:
  - Display a complete list of students and courses.
  - View individual student and course details.
- **Add New Records**:
  - Add new students and courses through user-friendly forms.
- **Edit Existing Records**:
  - Update student and course information using their respective forms.
- **Delete Records**:
  - Remove student or course entries by ID.
- **User-Friendly Navigation**:
  - Dynamic navigation bar highlighting the active route using Handlebars helpers.
- **Comprehensive Error Handling**:
  - Handles scenarios where no records are found or server errors occur.
- **Deployment**:
  - Hosted on **Cyclic.sh** for easy online access: [Live App](https://red-combative-elk.cyclic.app/).

## Technology Stack

- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Web framework for handling routes and server logic.
- **Handlebars.js**: Templating engine for rendering dynamic content.
- **Sequelize**: ORM (Object-Relational Mapping) for database interactions.
- **HTML/CSS**: Used for basic frontend structure and design.
- **Cyclic.sh**: Platform for deployment.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/college-management-app.git
   cd college-management-app
2. **Install Dependencies: Ensure you have Node.js installed, then run**:
   ```bash
   npm install
3. **Run the Application: Start the server with**:
   ```bash
   npm start
  The app will be available at http://localhost:8000 or on the port specified by the PORT environment variable.

# Usage

## Home Page (`/`)
Navigate to the homepage to access all features.

## Students
- **List**: `/students` shows all students.
- **Add**: `/students/add` to add a new student.
- **Details**: `/student/:studentNum` to view and edit a specific student.
- **Delete**: `/student/delete/:studentNum` to remove a student.

## Courses
- **List**: `/courses` displays all courses.
- **Add**: `/courses/add` to add a new course.
- **Details**: `/course/:id` to view and update course information.
- **Delete**: `/course/delete/:id` to remove a course.

# Error Handling
The application is equipped with error handling for cases such as:
- **Not Found**: Returns a `404` status if a requested record doesn't exist.
- **Server Errors**: Returns a `500` status with appropriate error messages when internal issues occur.

# Project Structure
- **app.js**: Main server script with routing and middleware setup.
- **modules/collegeData.js**: Module handling data operations.
- **views/**: Directory for `.hbs` view templates.
- **public/**: Contains static assets like CSS and images.
- **layouts/**: Holds Handlebars layout templates.

# License
This project is created and submitted as part of coursework at [Seneca College](https://www.senecacollege.ca/) and adheres to the college's [Academic Integrity Policy](https://www.senecacollege.ca/about/policies/academic-integrity-policy.html).

# Author
**Name**: Amit Thakuri  
**Date**: August 9, 2023  
**Online (Cyclic) Link**: [Live Demo](https://red-combative-elk.cyclic.app/)



