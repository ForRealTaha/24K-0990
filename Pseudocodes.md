**Pseudocode Lab Tasks**
1. Find if the number is multiple of 5.

START

PRINT “Enter Your Number”
INPUT Num1

SET Remainder to Num1 MOD 5

IF Remainder = 0 THEN
	PRINT Num1 & “ is a multiple of 5”
ELSE
	PRINT Num1 & “ is not a multiple of 5”
ENDIF

END

2. Check if a character is uppercase or lowercase.

START

PRINT “Enter your character”
INPUT character

IF character >= ‘A’ AND character <= ‘Z’ THEN
  PRINT “Character is uppercase”
ELSE
	IF character >= ‘a’ AND character <= ‘z’ THEN
		PRINT “Character is lowercase”
	ELSE
		PRINT “Suitable character not entered. Please try again”
	ENDIF
ENDIF

END

3. Create a small calculator which only does ‘+’ or ‘*‘Operations. (Hint: Take three variable inputs with one being used for the operator)

START

PRINT “Enter your first number”
INPUT Num1

PRINT “Enter your second number”
INPUT Num2

PRINT “Enter your operator”
INPUT opt

IF opt = “*” THEN
	SET final to Num1*Num2
ELSE
	SET final to Num1 + Num2

PRINT final

END

4. Check whether a given number is positive, negative, or zero.

START

PRINT “Enter a number”
INPUT Num1

IF Num1 = 0 THEN
	PRINT “Number is zero”
ELSE
	IF Num1 > 0 THEN
		PRINT “Number is positive”
	ELSE
		PRINT “Number is negative”
	ENDIF
ENDIF

END

5. Determine if a person is a teenager (between 13 and 19 years old).

START

PRINT “Enter your age”
INPUT Age

IF Age >= 13 AND Age <= 19 THEN
	PRINT “The person is a teenager”
ELSE
	PRINT “The person is not a teenager”
ENDIF

END

