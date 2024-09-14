**Name**: ISHITA KHURANA
**Company**: CODTECH IT SOLUTIONS
**ID**: CT08DS7876
**Domain**: Java Programming
**Duration**: September-August 2024
**Mentor**: NEELA SANTHOSH KUMAR

**Overview of the Project**
This Java code defines a Student class that represents a student's information, including their name, marks in five subjects, total marks, average, and GPA (Grade Point Average). The code provides methods to input the student's information, calculate the total marks, average, and GPA, and display the results.
Here's a step-by-step breakdown of how the code works:

**Class Variables and Methods**
The Student class has five instance variables:
name: a String to store the student's name
total, avg, and gpa: float variables to store the total marks, average, and GPA, respectively
marks[]: an array of float to store the marks in five subjects
The class has four methods:
input(): to input the student's name
markssub(): to input the marks in five subjects
calculate(): to calculate the total marks, average, and GPA
display(): to display the student's information, including their name, average, and GPA

**Main Method**
The main method creates an instance of the Student class, called ob.
It then calls the input(), markssub(), calculate(), and display() methods in sequence to input the student's information, calculate the total marks, average, and GPA, and display the results.

**Input Method**
The input() method prompts the user to enter the student's name and stores it in the name instance variable using the Scanner class.
The method uses a Scanner object to read the user's input and store it in the name variable.

**Marks Input Method**
The markssub() method prompts the user to enter the marks in five subjects and stores them in the marks[] array.
The method uses a for loop to iterate through the array and input the marks for each subject.
The marks are stored in the marks[] array, which has a length of 5.

**Calculate Method**
The calculate() method calculates the total marks, average, and GPA based on the marks input by the user.
The method uses a for loop to iterate through the marks[] array and calculate the total marks by summing up the marks in each subject.
The average is calculated by dividing the total marks by 5 (the number of subjects).
The GPA is calculated based on the average marks, using a predefined formula (e.g., 4.0 for 90-100%, 3.0 for 80-89%, etc.).

**Display Method**
The display() method displays the student's information, including their name, average, and GPA.
The method uses System.out.println() statements to print the student's name, average, and GPA to the console.

**Main Method**
The main method creates an instance of the Student class, called ob.
It then calls the input(), markssub(), calculate(), and display() methods in sequence to input the student's information, calculate the total marks, average, and GPA, and display the results.
