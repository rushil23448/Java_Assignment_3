Student Management System in Java

This Java program is a simple Student Management System that demonstrates the use of classes, array of objects, instance members, and constructors. It allows users to perform operations such as adding, displaying, searching, updating, and deleting student records.

Features

Add students with attributes like PRN, name, date of birth, and marks.
Display the list of all students.
Search for a student by PRN or name.
Update/edit student information.
Delete a student record.

class and function descriptions:

Student Class

The Student class represents a student with attributes such as PRN (11-digit number), name, date of birth, and marks. It has the following methods:

public Student(long prn, String name, String dob, double marks)
Constructor to initialize the Student object with provided PRN, name, date of birth, and marks.

public void display()
Method to display the details of a student, including PRN, name, date of birth, and marks.

StudentManagementSystem Class

The StudentManagementSystem class is the main class that contains the menu-driven program. It includes the following methods:

public static void main(String[] args)
The main method that runs the program. It displays a menu and executes the chosen operation until the user chooses to exit.

static void addStudent()
Method to add a new student to the studentList. It prompts the user for PRN, name, date of birth, and marks.

static void displayStudents()
Method to display the details of all students in the studentList.

static void searchByPRN()
Method to search for a student by PRN in the studentList.

static void searchByName()
Method to search for a student by name in the studentList.

static void updateStudent()
Method to update the details of a student in the studentList based on the provided PRN.

static void deleteStudent()
Method to delete a student from the studentList based on the provided PRN.

Usage

Follow the on-screen menu to interact with the program:

Add Student: Adds a new student to the list.
Display Students: Shows details of all students.
Search by PRN: Searches for a student by PRN.
Search by Name: Searches for a student by name.
Update/Edit Student: Modifies the details of an existing student.
Delete Student: Removes a student from the list.
Exit: Ends the program.
