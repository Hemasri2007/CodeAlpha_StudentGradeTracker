## CodeAlpha_StudentGradeTracker ##
# TASK-1
## Project Name :
    --  STUDENT GRADE TRACKER --
 
## Project Description :
   The Student Grade Tracker is a simple Java console-based application designed to manage student information and analyze their academic performance. It allows users to input multiple students names and marks, then automatically calculates the average, highest, and lowest marks. This project demonstrates the use of arrays, loops, and basic conditional logic in Java.

## Objectives :

 - To store and manage student details efficiently.
 - To calculate academic statistics such as average, highest, and lowest marks.
 - To practice Java fundamentals like arrays, loops, and Scanner input.
 - To generate a simple performance report for students.
 - To improve understanding of basic data processing in Java.
 
 ## Tools and Technologies Used :
      - Programming Language: Java
      - IDE: VS Code 
  # Concepts Used:
      - Arrays
      - Loops (for loop)
      - Conditional Statements (if conditions)
      - Scanner class for input handling
  Platform: Console-based application
## Features:

- Accepts dynamic number of students
- Stores student names and marks using arrays
- Calculates average marks
- Finds highest marks among students
- Finds lowest marks among students
- Displays a structured student performance report
- Simple and easy-to-use console interface

## How It Works:

 - The program starts and asks the user to enter the number of students.
 - It creates two arrays:
       - One for storing student names.
       - One for storing student marks
  - Using a loop, the program takes input for each student’s name and marks.
  - While taking input, it simultaneously:
       - Adds marks to total
       - Tracks highest marks
       - Tracks lowest marks
   - After input is completed:
       - Average marks are calculated using total / number of students
   - Finally, the program displays:
       - List of all students with marks
       - Average marks
       - Highest marks
       - Lowest marks
## Example

  ## Input:
<p align="center">
  <b>Input</b><br><br>
  Enter number of students: 3<br><br>

  Student 1<br>
  Enter Name: Hema<br>
  Enter Marks: 90<br><br>

  Student 2<br>
  Enter Name: Ravi<br>
  Enter Marks: 85<br><br>

  Student 3<br>
  Enter Name: Priya<br>
  Enter Marks: 95
</p>

 ## Output:
<p align="center">
  <b>Output</b><br><br>

  ----- Student Report -----<br>
  Name: Hema | Marks: 90<br>
  Name: Ravi | Marks: 85<br>
  Name: Priya | Marks: 95<br><br>

  Average Marks: 90.0<br>
  Highest Marks: 95<br>
  Lowest Marks: 85
</p>

## Future Improvements :

- Add grading system (A, B, C, etc.) based on marks
- Store data permanently using files or databases
- Add graphical user interface (GUI) using Java Swing or JavaFX
- Include subject-wise marks calculation
- Improve input validation (prevent invalid marks like negative or >100 values)
- Generate downloadable reports
## Conclusion :

   The Student Grade Tracker project successfully demonstrates how Java can be used to handle basic data processing tasks. It strengthens understanding of arrays, loops, and conditional logic while providing a foundation for more advanced student management systems.
## Author :
  Hema Sri
