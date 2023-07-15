# Employee-Assessment-System-Database

This is an Employee Management System project that allows you to manage employees, courses, enrollments, grades, and more. It provides functionalities to track employee enrollments in courses, record their grades, and generate summary reports.
<br>
<h3>Queries Include in .sql file</h3>
<ul>
a.	Pattern match search condition
  <br>
b.	Reading of Data from multiple tables
   <br>
c.	Sorting Results (ORDER BY Clause)
   <br>
d.	Using the SQL Aggregate Functions
   <br>
e.	Restricting groupings (HAVING clause)
   <br>
f.	Queries containing ANY and ALL keywords
   <br>
g.	Sub-queries or nested queries 
   <br>
h.	Simple join, Sorting a join, Three-table join, Outer joins
   <br>
i.	Create Updateable Views
   <br>
j.	Modifying views
 <br>

  
</ul>


## Table of Contents

- [Features](#features)
- [Database Schema](#database-schema)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create and manage employees, instructors, courses, enrollments, quizzes, assignments, projects, and grades.
- View employee details, course information, enrollment records, and grades.
- Perform various queries to retrieve specific data, calculate statistics, and sort results.
- Create updateable views for customized data representation.
- Modify views to include additional columns or change query logic.

## Database Schema

The project's database schema consists of the following tables:

- Instructors: Stores information about course instructors.
- Employees: Stores employee details.
- Courses: Stores course information and instructor assignments.
- Enrollments: Tracks employee enrollments in courses.
- Quizzes: Stores quiz details and their association with courses.
- Assignments: Stores assignment details and their association with courses.
- Projects: Stores project details and their association with courses.
- Grades: Records employee grades for quizzes, assignments, and projects.

## Installation

1. Clone the repository: `git clone https://github.com/ShahxHussain/employee-management-system.git`
2. Set up a database server (e.g., MySQL, PostgreSQL).
3. Create a new database.
4. Import the database schema and sample data from the SQL script provided.
5. Update the database connection details in the project's configuration file.
6. Install any necessary dependencies.

## Usage

1. Start the application by running the main program file.
2. Access the application through a web browser or command-line interface.
3. Use the provided functionalities to manage employees, courses, enrollments, and grades.
4. Execute queries to retrieve specific information, calculate statistics, and generate reports.
5. Modify views to customize data representation based on your requirements.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
