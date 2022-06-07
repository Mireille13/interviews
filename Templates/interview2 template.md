/**
 * Date: 
 * Interviewee: 
 * Emails: 
 * Interview #: 2
 * Prefered program: 
 * Cohort/Start Date: 
 * Notes: 
 * link: 
 */

// -------------->  - 2nd interview - //// -   <----------------//

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

# Level 1 Challenges

# Problem A: largestSwap
Time Started:

Prompt 1:
/*
Declare a variable 'myNums' and set it to an object.
On that object you will have two key-value pairs. One key will be 'favoriteNumber' and its value will be your favorite number.
The other key will be 'randomNumber' and its value will be 12.
*/

Prompt 2:
/*
Write a function 'largestSwap' that takes a two-digit number and determines if it's the largest of two possible digit swaps. 'largestSwap' should return a boolean.
For example, if 27 is our our input, we should return false because swapping the digits gives us 72, and 72 > 27.
Furthermore, if our input is 43 'largestSwap' should return true because swapping the digits gives us 34 and 43 > 34.
*/

Prompt 3:
// Check that your 'largestSwap' function is working correctly by passing the value of 'randomNumber' on your 'myNums' object to your 'largestSwap' function


# NOTES:
[+/-]



# Problem B: societyName
Time Started:

Prompt 1:
// Declare a variable 'names' and set it to an array with the values 'Chris', 'Samantha', 'Richard', and  'Kyle' in it.

Prompt 2:
/*
A group of friends have decided to start a secret society. The name will be the first letter of each of their names, sorted in alphabetical order.
Create a function 'societyName' that takes in an array of names and returns the name of the secret society.
For example, if our input is ['Adam', 'Sarah', 'Malcolm'] then 'societyName' should return the string 'AMS'
*/

Prompt 3:
// Check that your 'societyName' function is working correctly by passing the value of 'names' to the function 'societyName'

# NOTES:
[+/-]



# Problem C: isVowel/firstVowel
Time Started:

Prompt 1:
// Decare a variable 'randomString' and set it to the string 'Hello World'

Prompt 2:
/*
Create a function 'isVowel' that takes in a string (this string will be a single character) as an argument. "isVowel" should return true if the string is a vowel false if it is not. This function should consider letters a, e, i, o, and u to be vowels.
*/

Prompt 3:
/*
Create a function 'firstVowel' that uses your 'isVowel' function to return the index of the first vowel in a string.
For example, if our input to 'firstVowel' is 'apple' then 'firstVowel' should return 0.
If there is no vowel present in the string your function should return the string 'there is no vowel present'.
*/

# NOTES:
[+/-]



# Level 2 Challenges

# Problem A: concatWithSpace/shorten
Time Started:

Prompt 1:
/*
Create a function "concatWithSpace" that takes in two arguments (both will be strings). "concatWithSpace" should return the two strings concatenated with a space in between them.
For example, if the arguments are "hello" and "world" then "concatWithSpace" should return "hello world".
*/

Prompt 2:
/*
Create a function called "shorten". "shorten" takes three arguments (an array, a function, and an initial value). "shorten" is designed to shorten this array's multiple values to just one value by applying the callback function to each of the values in the array.
This is how it works:
- The shorten function will have an "accumulator value" which will initially be set to the initialValue argument. Its job is to accumulate the outputs of each call to the callback function.
- The array is iterated over, passing the accumulator value and the next array element to the callback function.
- The callback function's returned value becomes the new accumulator value
- The next loop executes with the new accumulator value.
*/

Prompt 3:
/*
Check that your 'shorten' function is working correctly by passing an array to it with the string values 'is', 'so', 'much' and 'fun!' as the first argument.
Pass your concatWithSpace function as our callback and the string 'Programming' as the initialValue argument. The result of this call to shorten should be the string 'Programming is so much fun!'
*/

# NOTES:
[+/-]



# Problem B: countTimes
Time Stated: 

Prompt 1:
/*
Create a function "countTimes" that takes in two arguments (an array and a search value). "countTimes" should return the number of times the search value is present in the array.

Example:
countTimes([1, 8, 9, 9, 10], 9) -> 2
*/

Prompt 2:
/*
Create a function called "wordSearchLetterCounter" that takes two arguments (a 2 dimensional array of letters known as our word search, and a letter that we are going to search for).
"wordSearchLetterCounter" should use your "countTimes" function to count the total number of times a letter show up in the word search.

Example:
wordSearchLetterCounter([
  ["D", "E", "Y", "H", "A", "D"],
  ["C", "B", "Z", "Y", "J", "K"],
  ["D", "B", "C", "A", "M", "N"],
  ["F", "G", "G", "R", "S", "R"],
  ["V", "X", "H", "A", "S", "S"]
], "D") ➞ 3
"D" shows up 3 times: twice in first row, once in third row.
*/

# NOTES:
[+/-]



# Problem C: changeCase
Time Started: 

Prompt 1:
/*
Create a function "changeCase" that takes in a letter as an argument, and returns the letter in the opposite case.

Examples:
changeCase('a') -> 'A'
changeCase('B') -> 'b'
*/

Prompt 2:
/*
Create a function "effectString" that takes in two arguments (a string and a callback function).
"effectString" should apply that callback function to each letter in the string and return out a new string.
*/

Prompt 3:
// Check to that your "effectString" is working properly by passing it the string "hello WORLD" and the callback function "changeCase"


# NOTES:
[+/-]



# Level 3 Challenges

# Problem A: checkerLogger
Time Started:

Prompt 1:
/*
Create a function "checkerLogger" that takes one argument (a function that returns a boolean value) The returned function should have the following behavior:
If the function is invoked with an argument, the checker callback function is invoked and its boolean result is returned.
If the function is invoked without any arguments, instead return a count of the number of times the callback function has been invoked and evaluated true or false.

Example:
const isOdd = num => num % 2 === 1;
const oddCounter = checkerLogger(isOdd);
oddCounter(); -> { true: 0, false: 0 }
oddCounter(3); -> true
oddCounter(2); -> false
oddCounter(); -> { true: 1, false: 1 }
*/

# NOTES:
[+/-]



# Problem B: countChar
Time Started:

Prompt 1:
/*
Create a function "countChar" that takes two arguments (an input string and a target string of length 1).
"countChar" will return the number of times the target string is found in the input string.
Example:
countChar('hello world', 'o'); -> 2
countChar('javascript', 'j'); -> 1
Note: Do not use any native JS methods, or loops.
*/

# NOTES:
[+/-]



# Problem C: passwordSafe
Time Started:

Prompt 1:
/*
Write a function "passwordSafe" that takes two arguments: a string which will be the password, and a value which will be the "safe". "passwordSafe" should return a function that takes in a password as a string.
If that password doesn’t match the one originally provided, return the string “You have entered the wrong password”. If the passwords do match, return the safe.

Example:
const mySafe = passwordSafe('myPassword', 'My Super Secret');
mySafe('wrongPassword') -> "You have entered the wrong password"
mySafe('myPassword') -> "My Super Secret"
*/

# NOTES:
[+/-]



# Level 4 Challenges

# Problem A: deepCopy
Time Started:

Prompt 1:
/*
Write a function 'deepCopy' that creates a deep copy of every level of a given object or array, and returns it, no matter deep the object is nested.
Example:
const tools = [{ editor: { favorite: { mine: { name: 'vscode' } } } }, { shell: 'zsh' }];
const copyOfTools = deepCopy(tools);
console.log(copyOfTools === tools);                                                           // -> false
console.log(copyOfTools[0] === tools[0]);                                                     // -> false
console.log(copyOfTools[0].editor === tools[0].editor);                                       // -> false
console.log(copyOfTools[0].editor.favorite === tools[0].editor.favorite);                     // -> false
console.log(copyOfTools[0].editor.favorite.mine === tools[0].editor.favorite.mine);           // -> false
console.log(copyOfTools[0].editor.favorite.mine.name === tools[0].editor.favorite.mine.name); // -> true
*/

# NOTES:
[+/-]



# Problem B: subsetSum
Time Started:

Prompt 1:
/*
Write a function 'subsetSum' that is given an array of integers and a target number. It should return true if there is a subset of the array that sums up to the target and returns false otherwise. A subset can be any size and the elements do not have to appear consecutively in the array.

Examples:
subsetSum([3, 7, 4, 2], 5)           -> true (3 + 2 = 5)
subsetSum([3, 34, 4, 12, 5, 12], 32) -> true (3 + 12 + 5 + 12 = 32)
subsetSum([8, 2, 4, 12], 13)         -> false
subsetSum([8, -2, 1, -3], 6)         -> true (8 + 1 + (-3) = 6)
*/

# NOTES:
[+/-]



# Problem C: debounce
Time Started:

Prompt 1:
/*
Write a function called 'debounce' that accepts a function and returns a new function that only allows invocation of the given function after 'wait' milliseconds have passed since the last time the returned function ran. Additional calls to the returned function within the 'wait' time should not be invoked or queued, but the timer should still get reset.

Example:
function giveHi() { return 'hi'; }
const giveHiSometimes = debounce(giveHi, 3000);
console.log(giveHiSometimes()); // -> 'hi'
setTimeout(function() { console.log(giveHiSometimes()); }, 2000); // -> undefined
setTimeout(function() { console.log(giveHiSometimes()); }, 4000); // -> undefined
setTimeout(function() { console.log(giveHiSometimes()); }, 8000); // -> 'hi'
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
