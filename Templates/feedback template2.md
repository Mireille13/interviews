NOTE:

[+] reads prompts out loud
[+] asks clarifying questions
[+] clear overall strategy
[+] followed by clear, detailed pseudocode
[+] keeps me in the loop of his thought process
[+] console logs variables to track what's happening in the code
[+] clarifies input and output at the beginning of the overall strategy

- ditches the pseudocode and starts coding while working out the overall strategy when stuck
- inefficient code - extra variables
- gets quiet when hitting a block


**_ GOOD _**

- Online Resources - used online resources when you were unsure about things and hitting a block. Kept me in the loop with what you were looking up.

- Syntax & Formatting - organized and formatted code that was easy to follow.

- Technical Communication - Read the prompts aloud. Verbalized your thought process. Asked clarifying questions. Used correct technical terms.

[+] inspect variables w/ DESCRIPTIONS

- Debugging & Testing - inspected the variables and control flow with descriptions to quickly isolate the issues during debugging.

- Testing - Tested edge cases to ensure your code worked as expected before moving on.

- Testing - inspected the variables and control flow and tested your code to ensure it worked as expected before moving on. 

- Has test edge cases in mind. Checks for empty arrays.

*** BAD ***

**_ Pseudocode _**

[-] no pseudocode

- Overall Strategy & Pseudocode - you did an excellent job explaining your thought process and communicating your overall strategy. However, should use pseudocode while working out your overall strategy. Ensure there are no missing key points before any actual code takes place. Your pseudocode should explain your overall strategy with all key elements in your logic. It should be written in short terms or simple English language that the programmers of all types will understand. It should not be able to be compiled into an executable program. There are many explaining videos in CSX. Watch how they give overall strategy and how they write pseudocode.

[has_Pseudocode]
- Overall Strategy & Pseudocode - You did a great job communicating your overall strategy. However, should work out your complete overall strategy with detailed pseudocode first before the actual coding takes place, not the other way around. Pseudocode should be written in short terms or simple English language that programmers of all types will understand. It should not be able to be compiled into an executable program. Instead, it acts as a guide or steps for the actual code. There are many explaining videos in CSX. Watch how they give overall strategy while pseudocode.

[has_Pseudocode_but_wayTooLong]
- Overall Strategy & Pseudocode - You did a great job communicating your overall strategy followed by pseudocode. However, the purpose of pseudocode is to guide your actual code. It should be written in short terms or sentences straight to the point instead of long sentences. Lastly, move each line of pseudocode inside the function and write each line of the actual code below it. There are many explaining videos in CSX. Watch how they give overall strategy while pseudocode.

[has_Pseudocode_but_missing_key_points]
- Overall Strategy & Pseudocode - You did a great job communicating your overall strategy, followed by clarifying input, output, and initial thoughts. However, the purpose of pseudocode is to guide your actual code. Should work out your complete overall strategy with detailed pseudocode first before the actual coding takes place (except the ones that the interviewer states to skip the pseudocode for simple prompts). There are many explaining videos in CSX. Watch how they give overall strategy while pseudocode.

[InputOutputInitialThoughts_ButNoPseudocode]
- Overall Strategy & Pseudocode - You did a great job communicating your overall strategy, followed by clarifying input, output, and initial thoughts. However, should work out your complete overall strategy with detailed pseudocode first before the actual coding takes place, not the other way around. The purpose of pseudocode is to guide your actual code. It should be written in short terms or sentences straight to the point instead of long sentences. Lastly, move each line of pseudocode inside the function and write each line of the actual code below it. There are many explaining videos in CSX. Watch how they give overall strategy while pseudocode.

[good_pseudocode_till_hard_problem]
- Overall Strategy & Pseudocode - You did a great job communicating your overall strategy, followed by clarifying input, output, and pseudocode when you know what to do. However, should continue to do so in situations you don't know what to do right off the bat.

**_ Tech Communication _**
[-] good till stuck

- Technical Communication - Great job on giving your overall strategies. However, there were moments of silence that left me in the dark with your thought process. Should continue to communicate your thought process when hitting a block or debugging. Should always read the prompts out loud and ask clarifying questions when needed.

- Technical Communication - you did an excellent job reading prompts aloud and verbalizing your thoughts when you know what to do. Should continue to do so when you hit a block or during the debugging process. Thursday Pair Programming workshops are highly recommended.

**_ Code Efficiency _**

[-] update inside Recursion [-]GET LENGTH:

- Code Efficiency - Avoid declaring unnecessary variables by updating the input values directly inside of the recursion function parameters. In checkerLogger, instead of declaring extra variables, you can directly declare these as key pair value inside of the output object. You can also increment the count by accessing the object value instead of declaring extra variables. Save the returned result from callback functions so you do not have to recall and run the same callback functions again later. For the inner function in closure, you can declare it as an anonymous function instead of declaring with another variable name.

[2ndTI-largestSwap]
- Code Efficiency - Avoid declaring unnecessary variables by updating the input values directly inside the recursion function parameters. In largestSwap instead of creating multiple variables, you can chain the methods together like so, const reversed = num.toString("").split().join(""). For functions that check conditions will return a boolean value by default. Instead of "if (num > reversedNum){return true}else {return false}", we can simply return num > reversedNum.

[-] converting string to an array to iterate
We can iterate a string directly with a for loop instead of converting it into an array.

[-] const/let
- Code Efficiency - should use const instead of let for num = 10.

[-] default boolean
- Code Efficiency - Should avoid declaring extra variables or if statements. For functions that check for conditions will return boolean by default. For example: function divBy100 (num) { return num % 100 === 0 };

 [-] 2 loops *** minAndMax ***
 In minAndMax, we can put all the functionalities in one loop instead of iterating the same array twice. 

[-] 2 push method in *** minAndMax ***
In minAndMax, we can chain two push methods together .push(min, max). We can also return an array that contains the min and max values, return [min, max] instead of declaring an extra output array.

*** minAndMax ***
In minAndMax, we can chain two push methods together results.push(smallest, largest). Or, we can just return an array that contains the two values like return [smallest, largest] instead of declaring the extra results array plus calling the two push methods.

[usesExtraSlice()] *** minAndMax ***
In minAndMax, instead of using the slice() method, we can start the for...loop at index 1.

[-] *** passAllTest *** - extra loop
Avoid declaring unnecessary data structures and iterations. For example, in passAllTests, when you pushed all the returned results into an array, you iterated the array and checked to see if there's a false. The same logic can apply to the array of callbacks as well. We can check if there's at least one result that returns false, otherwise return true.

[-] *** passAllTest *** - extra variable - .include()
In passAllTests, when you push all the returned results into an array, check if there's a false value using the include method. The same logic can apply to the array of callbacks directly as well. Can you check if there is a false value from the returned callback functions?

[-] *** passAllTest *** - return true inside the for loop
In passAllTests, watch where you return. A function needs a return statement to exit the thread of execution. Test your code to see the difference between returning your true statement inside the for loop versus outside.

[-] *** passAllTest *** - extra result variable assigned to true
In passAllTests, we can return false directly when we hit a returned false from the callbacks instead of declaring a variable "isTrue".

[-]usePortions
It was an interesting solution in usePortions! Also, checkout JavaScript native methods Number() and .join("") see if you can come up with a solution that can reduce steps, improve time complexity a little, and readability.

**_ Debugging _**

[-]

- Debugging - That was great that you tried to console log the variables to keep track of what was happening in your code. Should try going line by line in your code to understand the functionality fully. If still stuck, try white-boarding it out.

[ditch_old_code]
- Should avoid discord a strategy completely when it doesn't play out. You miss an opportunity to learn why it doesn't work.

[noVariables]

- Debugging - Try console logging the variables and use error messages in the console to track what is happening in your code. Go through your code line by line to eliminate the issues. If still stuck, try white-boarding it out.

**_ Closure & Recursion _**

- Closure & Recursion - Closure always returns another function. So, in checkerLogger, it should be returning the inner function, where the inner function will be returning either an object or a boolean value. Continue work on closure and recursion.

*** OVERALL Strategy ***
- Overall Strategy - For overall strategy, start with what information is provided, such as input/output, type of data, how many parameters and conditions the function need to pass, etc. Then go through each of the conditions we need to fulfill to get the desired outcome. Always ask clarifying questions. Try whiteboard it out if still stuck. With all the information you've gathered, then develop a strategy to execute your code.

*** OVERALL Strategy *** - strong but missing information from prompts 
- Overall Strategy - Try avoiding simple mistakes by starting with what information is provided, such as input/output, type of data, how many parameters and conditions the function need to pass, etc. Then go through each of the conditions we need to fulfill to get the desired outcome. Always ask clarifying questions when needed. Finally, develop a strategy to execute your code with all the information you've gathered.

*** Syntax&Formatting ***
- Syntax & Formatting - Make sure to check the difference between "==" and "===" operators. should use const instead of let for data structures like array and object. Should also use const when declaring an arrow function.  

*** Spelling_mistakes ***
- Try double-checking your spelling and the prompts to avoid simple mistakes.

*** strugle with callback ***
You seemed to struggle to apply callbacks on complex challenges. Highly recommend going through callbacks in CSX multiple times.

*** bad with everything ***
- JavaScript and programming experience - You seemed to struggle to apply callbacks on complex challenges. There were confusions in which arguments to pass in in the outer and inner functions in closure. Highly recommend going through higher-order functions, closure, and recursion in CSX multiple times.

*** FLOW ***
- JS Knowledge - Check out the difference between dot notation and bracket notation. Check out when not to use arrow functions.

- JS Knowledge - Check out the difference between dot notation and bracket notation, examples of primitive and composite data types, and refine your technical communication on closure.