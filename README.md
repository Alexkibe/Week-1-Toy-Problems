# Week-1-Toy-Problems
Student Grade Generator
This is a simple JavaScript function that generates a grade based on the given marks. The function takes in a single parameter marks, which is an integer representing the student's score.

Installation
To use this function, simply copy and paste the code into your JavaScript project.

Usage
To generate a grade, call the grade function and pass in the student's marks as an argument. The function will return a grade based on the following criteria:

A: marks > 79
B: marks >= 60 && marks <= 79
C: marks > 49 && marks <= 59
D: marks >= 40 && marks <= 49
E: marks < 40
Here's an example of how to use the function:

javascript
grade(78); // Returns "B"

Speed Detector
This is a simple speed detector that calculates the number of demerit points a driver should receive based on their speed.

How to Use
To use this function, simply call speedInKmph(speed) and provide the driver's speed in km/h as an argument. The function will then calculate the number of demerit points the driver should receive and output a message to the console.

Speed Limit and Demerit Points
The speed limit for this detector is 70 km/h. If the driver's speed exceeds the speed limit, they will receive demerit points based on the following formula:

demeritPoints = Math.floor((speed - speedLimit) / 5) * demeritPointsPer5Km;
For every 5 km/h above the speed limit, the driver will receive 1 demerit point.

If the driver receives 12 or more demerit points, their license will be suspended.

Output
The output of this function will be a message to the console. If the driver has received any demerit points, the message will be in the following format:


You have received [number] demerit points.
If the driver's license has been suspended, the message will simply say:


License suspended.
If the driver has not received any demerit points, the message will say:



Ok.
Example
Here's an example of how to use this function:



speedInKmph(90);
This will output the following message to the console:


You have received 4 demerit points.

Salary Calculator
This is a simple JavaScript program that calculates the net salary of an employee based on their basic salary, benefits, and various deductions.

Variables
The program defines two variables, basicSalary and benefits, which represent the employee's basic salary and benefits, respectively.

Tax Rates and Deduction Rates
The program also defines two arrays, taxRates and nhifDeductions, which contain the tax rates and NHIF deductions based on the employee's gross salary, respectively. In addition, the program sets the NSSF deduction rate as a constant.

Calculations
The program calculates the gross salary by adding the basic salary and benefits. It then calculates the tax (payee) deductions by iterating through the taxRates array and calculating the payee based on the employee's taxable income.

The program also calculates the NHIF deductions by iterating through the nhifDeductions array and finding the appropriate deduction based on the employee's gross salary. Finally, the program calculates the NSSF deductions based on the gross salary and the NSSF deduction rate.

The net salary is calculated by subtracting the total deductions (payee, NHIF, and NSSF) from the gross salary.

Output
The program outputs the gross salary, payee (tax), NHIF deductions, NSSF deductions, and net salary to the console.
