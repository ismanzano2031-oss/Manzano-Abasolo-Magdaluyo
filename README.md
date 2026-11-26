PROJECT PROPOSAL
Project Title

Project Deadline Tracker: A Program for Managing and Monitoring Project Deadlines

1. Problem Statement

Managing project deadlines can become difficult, especially when students have multiple projects with different due dates. Without an organized way of recording deadlines, students may forget important submission dates or have difficulty keeping track of their tasks.

The Project Deadline Tracker is a Python-based program designed to help users record and monitor project deadlines. It allows users to enter a project name and its corresponding deadline, display the recorded information, and reset the date when necessary.

The project demonstrates basic Python programming concepts, including functions, user input, output statements, loops, regular expressions, and date handling.

2. Project Objectives

The project aims to:

Develop a Python program that allows users to enter project names and their corresponding deadlines.
Display project information and deadlines in a clear and organized format.
Implement functions to organize the program's operations.
Use loops to allow users to enter multiple project deadlines.
Apply regular expressions to validate user responses.
Utilize Python's datetime module to handle and format dates.
Provide an option to reset or enter another project deadline.
3. Planned Features
Enter Project Name – Allows users to input the name of their project.
Set Project Deadline – Allows users to enter the month, day, and year of the project's deadline.
Display Project Information – Shows the project name and its corresponding deadline.
Reset Project Deadline – Allows users to enter another project deadline.
Input Validation – Checks user responses to ensure that the entered information follows the expected format.
Repeat Function – Uses a while loop to repeat the program when the user wants to enter another deadline.
4. Planned Inputs and Outputs
Inputs
Project Name
Deadline Month
Deadline Day
Deadline Year
User response (Yes or No)
Outputs
Project name displayed in uppercase letters
Formatted project deadline
Reset confirmation
Input validation messages
Program termination message
5. Programming Concepts

The project will utilize the following Python concepts:

Python Concept	Purpose
Functions	Organizes the program's operations
Input Statements	Accepts the project name and deadline
Output Statements	Displays project information
While Loop	Allows users to repeat the program
Regular Expressions (re)	Validates the user's response
Datetime Module	Handles and formats project deadlines
Variables	Stores project information and deadline values
Conditional Statements	Controls the program based on user responses
6. Program Logic

The program begins by asking the user to enter the project name and its deadline, including the month, day, and year.

After receiving the inputs, the program displays the project name in uppercase letters and shows the corresponding deadline in a readable date format.

Once the information has been displayed, the program asks the user whether they want to reset the date. If the user answers Yes, the program repeats the process and allows them to enter another project name and deadline.

If the user answers No, the program terminates.

7. Pseudocode
text
START

DEFINE FUNCTION project_deadline()

    Ask user to enter Project Name
    Ask user to enter Deadline Month
    Ask user to enter Deadline Day
    Ask user to enter Deadline Year

    Display Project Name in uppercase
    Display formatted Project Deadline

END FUNCTION

CALL project_deadline()

Ask user if they want to reset the date

WHILE answer is YES

    CALL project_deadline()

    Ask user if they want to reset the date

END WHILE

Display "Program Terminated"

END

8. System Wireframe

Project Deadline Tracker – Main Interface

text

         PROJECT DEADLINE TRACKER

Enter Project Name:

Enter the Month of Its Deadline:

Enter the Day of Its Deadline:

Enter the Year of Its Deadline:

          PROJECT INFORMATION

Project Name:

Project Deadline:

Do you want to reset the date?
(Yes/No):

9. Input and Output Example

Sample Program Execution

text
Enter Project Name: Computer Science Project

Enter the Month of Its Deadline: 12
Enter the Day of Its Deadline: 15
Enter the Year of Its Deadline: 2026

Project Name: COMPUTER SCIENCE PROJECT
Deadline: December 15, 2026

Do you want to Reset the Date? Yes


If the user enters Yes, the program will ask for another project name and deadline.

If the user enters No, the program will stop running.

10. Flowchart Description

The flowchart will be created using Flowgorithm. It will illustrate the sequence of the Project Deadline Tracker, including:

Start the program.
Ask the user to enter a project name.
Ask for the deadline month, day, and year.
Display the project name in uppercase.
Format and display the project deadline.
Ask the user whether they want to reset the date.
If Yes, repeat the process.
If No, terminate the program.

Flowchart Image: To be inserted.

11. GitHub Repository

Project Repository:

https://github.com/ismanzano2031-oss/Manzano-Abasolo-Magdaluyo

12. Project Team Members
Samuel Manzano
Elijah Abasolo
Alfonso Magdaluyo

END OF PROJECT PROPOSAL
