# Algorithm Lab Tasks
1. Implement an algorithm to determine if a given year is a leap year. A leap year is divisible by 4, but not divisible by 100, except if it is also divisible by 400.

+ Step 1: Ask the user to enter Year
+ Step 2: Set remainder1 to (Year modulo (MOD) 4)
+ Step 3: Set remainder2 to (Year modulo(MOD) 100)
+ Step 4: Set remainder3 to (Year modulo(MOD) 400)
+ Step 5: if remainder1 is equal to zero and remainder2 is not equal to zero then skip to step 8.
+ Step 6: if remainder1 is equal to zero and remainder2 is equal to zero and remainder3 is equal to zero then skip to step .8
+ Step 7: if remainder2 is equal to zero and remainder3 is not equal to zero then skip to step 9.
+ Step 8: Print “Year is a leap year” and then end the program.
+ Step 9: Print “Year is not a leap year” and then end the program.


2. Implement an algorithm to count the number of occurrences of each character in a given string.

+ Step 1: Ask the user to input a string and store it in variable myString.
+ Step 2: Create counter variable for all characters that can occur
+ Step 2: Loop for n times where n is the length of myString.
+ Step 3: Extract each character from the string using the appropriate built-in function.
+ Step 4: Check which character shows up and increment its counter variable.
+ Step 5: Once the loop ends, print all the counter variables along with the character.


3. Write an algorithm to calculate x raised to the power y (i.e., x y ) without using built-in
power functions.

+ Step 1: Ask the user to enter x
+ Step 3: Ask user to enter y
+ Step 4: Set counter to zero
+ Step 5: Set power as 1
+ Step 6: Set power as (Power * x)
+ Step 7: Set counter as (counter + 1)
+ Step 8: if counter is less than y then jump to step 4 otherwise continue
+ Step 9: Print power


4. Calculate the area of a circle given its radius r.

+ Step 1: Ask user to enter the radius of circle, r.
+ Step 2: Set the constant PI as (3.14)
+ Step 3: Set Area as (PI x r x r)
+ Step 4: Print Area.

5. Find the median of three given numbers.

+ Step 1: Ask the user to enter Num1.
+ Step 2: Ask the user to enter Num2.
+ Step 3: Ask the user to enter Num3.
+ Step 4: Set Average as ((Num1 + Num2 + Num3) / 3).
+ Step 5: Print Average.

