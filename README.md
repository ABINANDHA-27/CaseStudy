# University Course Management System

Developed a menu-based console application to assess your proficiency in Core Java, MySQL, and JDBC. The application will simulate a university course management system, allowing users to manage courses, students, and enrollments.


#Tools Requirement
1.Eclipse:2024-06 (4.32.0)
2.Mysql Workbench: 8.0.38


#How to import this project
1.Start Eclipse
2.Import the file(File-> Import)
3.Click General, select the Existing Projects into workspace and click next.
4.Select the root directory and click Fnish.


#How to build this project
1.Select Project and click Build All.
Note:
Port 3306 is the default port for the MySQL Workbench.


#How to eun this project
1.Select Rub and click Run
2.The console will be popped up.

#Sample output

University Course Management System
1. Manage Courses
2. Manage Students
3. Manage Enrollments
4. Exit
Enter your choice: 1
Course Management
1. Add Course
2. View Course
3. Update Course
4. Delete Course
5. Back to Main Menu
Enter your choice: 3
Enter course ID: 34256
Enter new course name or enter old one: Python
Enter new instructor or enter old one: Suganya
Enter new schedule or enter old one: SATURDAY(3PM-5PM)
Enter new location or enter old one: A402
load
Course updated successfully.
Course Management
1. Add Course
2. View Course
3. Update Course
4. Delete Course
5. Back to Main Menu
Enter your choice: 4
Enter course ID: 35
load
Course deleted successfully.

University Course Management System
1. Manage Courses
2. Manage Students
3. Manage Enrollments
4. Exit
Enter your choice: 2
Student Management
1. Register Student
2. View Student
3. Update Student
4. Delete Student
5. Back to Main Menu
Enter your choice: 2
Enter student ID: 3
load
Student ID: 3
Student Name: Surya
Email: surya24@gmail.com
Major: ECE
Year: 2022

Enrollment Management
1. Enroll Student
2. View Enrollment
3. Update Enrollment
4. Withdraw Student
5. Back to Main Menu
Enter your choice: 1
Enter enrollment ID: 1
Enter student ID: 1
Enter course ID: 31
Enter enrollment date (YYYY-MM-DD): 2024-07-15
Enter grade: A
load
Student enrolled successfully.
Enrollment Management
1. Enroll Student
2. View Enrollment
3. Update Enrollment
4. Withdraw Student
5. Back to Main Menu
Enter your choice: 3
Enter enrollment ID: 1
Enter new enrollment date (DD-MM-YYYY) or enter the old one: 2024-07-15
Enter new grade or enter the old one: A+
load
Enrollment updated successfully.
