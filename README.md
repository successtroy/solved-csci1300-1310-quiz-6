Download Link: https://assignmentchef.com/product/solved-csci1300-1310-quiz-6
<br>
Write a function that takes two integers as inputs, where the first integer is the numerator and the second is the denominator.  The function should do the following:

If the denominator divides evenly into the numerator, return the

string “clean divisor”

If the denominator doesn’t divide evenly into the numerator, return

the string “dirty divisor”

If the denominator is 0 and the numerator is nonzero, return the

string “cannot divide by zero”

If the denominator and the numerator are both zero, return the string

“0/0 is not defined”

Use the following function definition: def theDivider(num, den):

Examples:

theDivider(14, 7) returns “clean divisor” theDivider(12, 9) returns “dirty divisor” theDivider(9, 0) returns “cannot divide by zero” theDivider(0, 0) returns “0/0 is not defined