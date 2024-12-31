# CODEALPHA-TASK1

NAME : PHANI GOPI CHAND GOLI

STUDENT ID:CA/D1/1476

DOMAIN: JAVA PROGRAMMING

#OVER VIEW OF THIS TASK
Import necessary classes:

java.util.ArrayList: To store the student grades.
java.util.Scanner: To get user input.
Create Scanner object:

Scanner scanner = new Scanner(System.in);
This allows you to read input from the console.
Create ArrayList to store grades:

ArrayList<Double> grades = new ArrayList<>();
This creates an empty ArrayList to hold the student grades (using Double for floating-point values).
Get number of students:

Prompt the user to enter the number of students.
Read the input using scanner.nextInt().
Get grades for each student:

Use a for loop to iterate through the number of students.
Prompt the user to enter the grade for each student.
Read the grade using scanner.nextDouble().
Add the grade to the grades ArrayList using grades.add(grade).
Calculate average grade:

Initialize a sum variable to 0.
Use an enhanced for loop to iterate through the grades ArrayList.
Add each grade to the sum.
Calculate the average by dividing sum by the numStudents.
Find highest and lowest grades:

Initialize highest and lowest variables to the first grade in the grades ArrayList.
Use an enhanced for loop to iterate through the grades ArrayList.
Compare each grade with the current highest and lowest values.
Update highest and lowest if a new higher or lower grade is found.
Display results:

Print the calculated average, highest, and lowest grades to the console.
Close Scanner:

scanner.close();
This releases system resources associated with the Scanner object.
This program effectively demonstrates how to use an ArrayList to store and process student grades, calculate their average, and find the highest and lowest scores
