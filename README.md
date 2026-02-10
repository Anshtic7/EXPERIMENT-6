# EXPERIMENT-6

NAME: ANSH PRATAP SINGH

PRN:- 25070123143

AIM: STUDY OF CONDITIONAL STATEMENTS IN PYTHON

THEORY:-

Conditional statements in Python are used to control the flow of a program based on certain conditions. They allow the program to make decisions and execute different blocks of code depending on whether a condition evaluates to True or False.

Python mainly uses if, if-else, and if-elif-else statements for decision-making. Conditions are formed using comparison operators (==, >, <, >=, <=, !=) and logical operators (and, or, not). Python relies on proper indentation to define conditional blocks, making the code clear and readable.

Conditional statements are widely used in real-life applications such as grading systems, eligibility checks, and validation processes.

Algorithm: Check Whether a Number is Positive, Negative, or Zero.

Start

Read an integer number from the user and store it in num.

If num is greater than 0, display â€œThe number is positive.â€

Else if num is less than 0, display â€œThe number is negative.â€

Else, display â€œThe number is zero.â€

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Check Whether a Number is Zero, Even, or Odd

Start

Read an integer number from the user and store it in num.

If num is equal to 0, display â€œThe number is zero.â€

Else if num modulo 2 is equal to 0, display â€œThe number is even.â€

Else, display â€œThe number is odd.â€

STOP

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Find the Largest of Three Numbers

Start

Read three numbers from the user and store them in variables a, b, and c.

If a is greater than or equal to both b and c, assign a to largest.

Else if b is greater than or equal to both a and c, assign b to largest.

Else, assign c to largest.

Display the value of largest.

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Determine Grade Based on Score

Start

Read the score from the user and store it in score.

If score is greater than or equal to 90, assign grade A.

Else if score is greater than or equal to 75, assign grade B.

Else if score is greater than or equal to 60, assign grade C.

Else if score is greater than or equal to 40, assign grade D.

Else, assign grade FAIL.

Display the grade corresponding to the score.

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Check Whether a Year Is a Leap Year

Start

Read the year from the user and store it in year.

If the year is divisible by 4 and not divisible by 100, or divisible by 400, then:

Display â€œThe year is a leap year.â€

Else:

Display â€œThe year is not a leap year.â€

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Gross Salary Calculation

Start

Read the basic salary

If basic salary ≤ 10000, then

--->a. Set HRA rate = 0.20

--->b. Set DA rate = 0.80

Else if basic salary ≤ 20000, then

--->a. Set HRA rate = 0.25

--->b. Set DA rate = 0.90

Else

--->a. Set HRA rate = 0.30

--->b. Set DA rate = 0.95

Calculate HRA = Basic Salary × HRA rate

Calculate DA = Basic Salary × DA rate

Calculate Gross Salary = Basic Salary + HRA + DA

Display Basic Salary, HRA, DA, and Gross Salary

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Income Tax Calculation Based on Annual Income

Start

Read the annual income

If annual income ≤ 250000, then

--->a. Set tax rate = 0%

--->b. Set tax amount = 0

Else if annual income ≤ 500000, then
--->a. Set tax rate = 5%
--->b. Calculate tax amount = (annual income − 250000) × tax rate

Else if annual income ≤ 1000000, then

--->a. Set tax rate = 20%

--->b. Calculate tax amount = (250000 × 5%) + (annual income − 500000) × tax rate

Else

--->a. Set tax rate = 30%

--->b. Calculate tax amount = (250000 × 5%) + (500000 × 20%) + (annual income − 1000000) × tax rate

Display annual income

Display applicable tax rate

Display calculated tax amount

Stop


Algorithm: Check Whether a Letter is Vowel or Consonant

Start

Read a character from the user

Check if the length of the input is equal to 1 and the character is an alphabet

If the condition in step 3 is true, then

--->a. Check if the character is one of the vowels (a, e, i, o, u)

--->b. If yes, display “The letter is a vowel”

--->c. Else, display “The letter is a consonant”

Else

--->a. Display “Please enter a single alphabet character”

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: Increment a Date by One Day

Start

Read the date string in YYYY-MM-DD format

Split the date string using the - separator into year, month, and day

Convert year, month, and day into integers

Check if the month is between 1 and 12 and the day is between 1 and 31

If the condition in step 5 is false, display “Invalid date components” and stop

Else

--->a. Increment the day by 1

Determine the number of days in the current month:

--->a. If month is 1, 3, 5, 7, 8, 10, or 12, set days = 31

--->b. If month is 4, 6, 9, or 11, set days = 30

--->c. If month is 2, then

----->i. Check if the year is a leap year

----->ii. If leap year, set days = 29

----->iii. Else, set days = 28

If the day exceeds the number of days in the current month, then

--->a. Set day = 1

--->b. Increment the month by 1

If the month exceeds 12, then

--->a. Set month = 1

--->b. Increment the year by 1

Display the original date

Display the incremented date

Stop

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
CONCLUSION:-
In this experiment, various Python programs were implemented to understand and apply fundamental programming concepts such as input/output operations, conditional statements, arithmetic calculations, logical decision-making, and exception handling. The programs demonstrated real-life problem solving, including salary calculation, income tax computation, character validation, and date manipulation. Through this experiment, clarity was gained on using if-elif-else structures, validating user input, handling special cases like leap years, and managing runtime errors using try and except. Overall, the experiment enhanced logical thinking, improved coding skills, and provided practical exposure to writing efficient and structured Python programs.
