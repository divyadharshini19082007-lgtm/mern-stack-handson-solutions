# Activity 2: Logic Building Challenge Students solve progressively complex logical problems using flowcharts and pseudocode before implementing them in code.
# Solution
In this activity, students solve a problem step by step before writing the actual program.
Example: Check whether a number is Even or Odd
Step 1: Algorithm
1. Start the program.
2. Get a number from the user.
3. Check whether the number is divisible by 2.
4. If the remainder is 0, print “Even Number.”
5. Otherwise, print “Odd Number.”
6. Stop the program.
Step 2: Flowchart
Start
Input number N
Is N % 2 == 0?
Yes
Print Even

No
Print Odd


Stop

Step 3: Pseudocode
START
INPUT N

IF N % 2 == 0 THEN
    PRINT "Even Number"
ELSE
    PRINT "Odd Number"
END IF

STOP


Step 4: Python program
n = int(input("Enter a number: "))if n % 2 == 0:    print("Even Number")else:    print("Odd Number")



Sample output:
Enter a number: 8
Even Number


Additional practice problems
Students can solve these problems in increasing order of difficulty.
Level	Problem
1. Easy	Add two numbers
2. Easy	Check whether a number is positive or negative
3. Medium	Find the largest of three numbers
4. Medium	Check whether a year is a leap year
5. Advanced	Calculate the factorial of a number
Expected outcome: Students learn to break a problem into smaller steps, represent the logic using flowcharts and pseudocode, and convert the solution into executable code.
Conclusion: Logic building helps students develop computational thinking and write programs accurately and efficiently.
