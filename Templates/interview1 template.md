/**
 * Date: 
 * Interviewee: 
 * Emails: 
 * Interview #: 1
 * Prefered program: 
 * Cohort/Start Date: 
 * Notes: 
 * link: 
 */

// -------------->  - 1st interview - //// -   <----------------//

# REQUIRED FOR EVERY INTERVIEW: BRIEF THE APPLICANT
"I will paste an endless series of increasingly difficult challenges into the editor.
Your task is to figure them out as best as you can, and remember that we're looking for
qualities beyond how many questions you get through, such as technical communication and engineering best practices.

- Feel free to use any online resources that you normally would, e.g. Google, Stack Overflow, documentation pages.
Just don't look up the solution directly. And when you do look something up, let me know what you are looking up
so I can understand your thought process. There are no penalties for looking things up.

- There are also no penalties for errors, so don't be afraid to run your code with an expected outcome
and use any error messages to your advantage in refactoring to get the desired outcome.

- Remember the importance of testing your code as some of the problems will build on each other,
so you want to make sure it works before moving on.

- Lastly, be sure to verbalize your thought process, as your technical communication is something we're looking for.
As you're thinking through it, be sure to keep me updated on your overall strategy. This will help me to assess
how you might work in a pair programming session or group environment.

- I will be having you share your screen with me through the duration of the interview,
so please close out of all unnecessary screens and turn off any distracting notifications.

- I'm not able to give any technical feedback today, but you will receive feedback and the result of your interview
directly from an Admissions Team Member within one week. We'll spend the last few minutes of the interview on any
non-technical questions you may have.

- Do you have any questions now regarding the format of the interview?"

Set timer for 50 mins

Confirm these things before starting
- INTERVIEWEE'S NAME:
- INTERVIEWEE'S EMAIL:
- PREFERRED COHORT:
- INTERVIEW NUMBER:

# Technical Interview Notes:

Level 1 Challenges

# Problem A: addNumbers
Time Started:

Prompt 1:
// Declare a variable 'number' and set it to the value 10.

Prompt 2:
/*
Create a function 'addNumbers' that takes a number as an argument. 'addNumbers' should add up all the numbers from 1 to the number you passed to the function.
For example, if the input is 4 then your function should return 10 because 1 + 2 + 3 + 4 = 10.
*/

Prompt 3:
// Check that your 'addNumbers' function is working correctly by passing your variable 'number' to the 'addNumbers' function


# NOTES:
[+/-]



# Problem B: minAndMax
Time Started:

Prompt 1:
// Declare a variable 'randomNums' and set it equal to an array that contain the numbers 1, 14, 7, 21, and -6.

Prompt 2:
/*
Create a function 'minAndMax' that takes an array of numbers and returns both the smallest and largest number in an array, in that order.
NOTE: do not use the native Math.min or Math.max methods. For example minAndMax([7, 68, 2, 19]) should return the array  [2, 68]
*/

Prompt 3:
//  Check that your 'minAndMax' function is working correctly by passing your variable 'randomNums' to the 'minAndMax' function


# NOTES:
[+/-]



# Problem C: charCount
Time Started:

Prompt 1:
// Declare a variable 'myString' and set it equal to the string 'I love programming'

Prompt 2:
/*
Create a function 'charCount' that takes two arguments (the first argument is a single character) and
returns the number of times the character is found in the second argument.
For example, charCount('i', 'Codesmith') should return the number 1
*/

Prompt 3:
/*
Check that your 'charCount' function is working correctly by passing the string 'o' as the first argument
and your variable 'myString' as the second argument to the 'charCount' function
*/

# NOTES:
[+/-]



# Level 2 Challenges

# Problem A: passAllTests & associated functions
Time Started:

Prompt 1:
/*
Create a function "between50And500" that takes a number as an argument.
"between50And500" should return a true if the number passed to it is between 50 and 500 exclusive.
For example, if the input is 45 then your function should return false and if the input is 472 it should return true.
*/

Prompt 2:
/*
Create a function "divBy100" that takes a number as an argument.
"divBy100" should return a true if the number passed to it is divisible by 100.
For example, if the input is 120 then your function should return false and if the input is 600 it should return true.
*/

Prompt 3:
/*
Create a function "negativeOrEven" that takes a number as an argument.
"negativeOrEven" should return a true if the number passed to it is a negative number OR it is an even number.
For example, if the input is 7 then your function should return false and if the input is -3 it should return true.
*/

Prompt 4:
/*
Create a function "passAllTests" that takes an array of functions and another value as arguments.
Each function in your array will return a boolean value. "passAllTests" should pass your value argument to each function.
If all functions in your array return true then "passAllTests" will return true. Otherwise "passAllTests" should return false
*/

Prompt 5:
/*
Use your "passAllTests" function to test if the number 300 is greater than the number 50 and less than the number 500, divisible by 100, and a negative number OR even. Then test the number 250.
*/


# NOTES:
[+/-]



# Problem B: addOne/subtractOne/two potions
Time Started:

Prompt 1:
// Create a function "addOne" that takes a number as and argument and returns that number plus one

Prompt 2:
// Create a function "subtractOne" that takes a number as and argument and returns that number minus one

Prompt 3:
/*
There are two types of potions:
Growing potion: "A"
Shrinking potion: "B"
If "A" immediately follows a digit, add 1 to the digit using your "addOne" function
If "B" immediately follows a digit, subtract 1 from the digit using your subtractOne function
Create a function "usePotions" that returns a string according to these rules, removing the potions once they've been consumed.

Example:
usePotions("3A78B51") ➞ "47751"
  3 grows to 4, 8 shrinks to 7
usePotions("9999B") ➞ "9998"
usePotions("9A123") ➞ "10123"
usePotions("567") ➞ "567"
*/

# NOTES:
[+/-]



# Problem C: isPalindrome
Time Started:

Prompt 1:
/*
Define a function "isPalindrome" that takes a string, and returns a boolean value indicating whether the string is a palindrome
(a palindrome is any string that has the same value when reversed - for example, "LEVEL" or "RACECAR")
*/

# NOTES:
[+/-]



# Level 3 Challenges

# Problem A: add (closure)
Time Started:

Prompt 1:
/*
Create a function "add" that takes an argument (a number) and returns a function.
The returned function should also take one argument (a number) and return the sum of its argument and the argument that was originally past to "add"

Example:
const addBy10 = add(10)
addBy10(20) -> 30
*/

# NOTES:
[+/-]



# Problem B: getLength
Time Started:

Prompt 1:
// Write a function "getLength" that returns the length of a string. Accomplish this without using any loops, native JS methods, or the length property.

NOTES:
[+/-]



# Problem C: itemRetriever
Time Started:

Prompt 1:
/*
Declare function "itemRetriever" that returns function that when called,  will return one of my favorite authors.
The function "itemRetriever" will take two argument (an array of objects and a string that will represent a key).
When the returned function is called it should return the next object in the array at the key that was passed to "itemRetriever".
example.

const favoriteAuthors = [
  { name: 'Earnest Hemingway' },
  { name: 'Agatha Christie' },
  { name: 'J.K. Rowling' },
  { name: 'Steven King' },
];

const nextAuthor = itemRetriever(favoriteAuthors, 'name');
nextAuthor() -> 'Earnest Hemingway'
nextAuthor() -> 'Agatha Christie'
*/

# NOTES:
[+/-]



# Level 4 Challenges

# Problem A: transpose
Time Started:

Prompt 1:
/*
Write a function called 'transpose' that accepts a two dimensional array and returns a transposed version of that array.
Example:
const twoDimArray = [ ['fred', 'barney'], [30, 40], [true, false] ]
console.log(transpose(twoDimArray)); // -> [['fred', 30, true], ['barney', 40, false]]
*/

# NOTES:
[+/-]



# Problem B: rotateGrid
Time Started:

Prompt 1:
/*
Write a function 'rotateGrid' that is given an NxN grid of elements represented by a 2D array, and outputs a grid equivalent to the same grid rotated 90 degrees clockwise.
Example:
const sampleGrid = [ [1, 2, 3], [4, 5, 6], [7, 8, 9] ]
console.log(rotateGrid(sampleGrid)); // -> [ [7, 4, 1], [8, 5, 2], [9, 6, 3] ]
*/

# NOTES:



# Problem C: balancedBrackets
Time Started:

Prompt 1:
/*
Write a function called 'balancedBrackets' that takes a string of text and returns true if the parentheses are balanced and false otherwise.
Non-bracket characters should not affect the logic. Make your solution work for all types of brackets: () [] {}

Examples:
balancedBrackets(" { }    n");                           // -> true
balancedBrackets("hi][  ");                              // -> false
balancedBrackets("[{random words and such}]");           // -> true
balancedBrackets("[The]Rains(In){Spain}");               // -> true
balancedBrackets("[({}Call me Ishmael)]");               // -> true
balancedBrackets("[(]{)}");                              // -> false
balancedBrackets(" gibberish { howdy: partner() }");     // -> true
balancedBrackets(" isThisAFunction?() { notReally();");  // -> false
*/

# NOTES:
[+/-]



# Free Flow Questions:

Use the last 10 or 15 mins to ask some free flow questions.
Free flow questions are to get a better sense of the applicant's knowledge of JavaScript.
These are some common questions to ask, but will be different based on the interviewee:

- What is the difference between a parameter and an argument.
- What is Hoisting?
- Can you describe closure to me?
- var vs let vs const.
- What is the difference between a console log and a return statement?
- How would you explain recursion to a beginner?
- Do you know what a base case is?
- What is the difference between a callback and an anonymous function?
- At a high level, what does reduce/map/filter do? 
- What is the difference between pass by value and pass by reference?
- What is a callback? What is a higher-order function?
- Can you explain the difference between bracket notation and dot notation? When might you use one over the other?
- What is the difference between map, forEach, and a regular loop?
- What is the difference between arrow function and regular function declaration?
- What are some examples of primitive and composite data types?
- What is the difference between return/break/continue?
- What is a method vs a property?

# JavaScript Experience:
# Technical Communication:
# Non-Technical Communication:
# Analytical Problem Solving:
# How Do They Handle Working Through Blocks:

# Last Problem COMPLETED:

# Recommendation:


# Things Done Well
1 -
2 -
3 -

# Things To Improve On
1 -
2 -
3 -

# Additional Notes for Admissions Team

# Red Flags