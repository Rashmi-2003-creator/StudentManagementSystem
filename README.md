<h1 align="center">Student Management System</h1>
<h4 align="center">A simple console based DBMS project to handle <strong>CRUD</strong> operations.</h4>


## About

This is a console-based Student Management System, which is a simple application designed to manage student records, including creating, updating, and deleting student information. Additionally, it allows for the assignment of courses to students, inserting student marks, calculating GPA, and viewing available courses and departments.

### Key functionalities of this Student Management System include:

1. **Create Student**: Users can input a student's ID, first name, last name, date of birth, and department ID to create a new student record in the database.

2. **Show Students**: This function retrieves and displays a list of all students stored in the database, including their basic information like name, date of birth, and department ID.

3. **Update Student**: Users can update the information of an existing student by providing their ID and modifying their first name, last name, date of birth, and department ID.

4. **Delete Student**: Allows the removal of a student record by specifying the student's ID.

5. **Add Course to Student**: This feature allows users to assign courses to students by selecting a student's ID and a course ID from a list of available courses.

6. **Insert Marks and Calculate GPA**: Users can enter marks for a student in a specific course, and the system will automatically calculate the GPA based on the provided marks.

7. **Search Student**: This function allows users to search for a specific student by their ID and displays detailed information about the student, including the courses they are enrolled in and their corresponding grades.

8. **View Courses and Departments**: Users can view a list of available courses and departments, and they can also insert new courses and departments.

The code interacts with a SQL Server database using SQL commands for data retrieval, insertion, updating, and deletion. It includes error handling to provide feedback on the success or failure of database operations.

Overall, this Student Management System serves as a basic tool for managing student information and academic records, making it useful for educational institutions or organizations that require a straightforward means of handling student data. Further improvements could include enhanced user interface features and additional functionalities like grade reporting, student enrollment management, and data analytics.

## Dependencies

- C#
- .NET SDK
- Microsoft SQL Server
- Microsoft Data.SqlClient


## How to use

1. Clone the repository
2. Install C# Dev Kit
3. Run the project