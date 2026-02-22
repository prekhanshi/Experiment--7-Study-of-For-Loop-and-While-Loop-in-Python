# Experiment--7

# Name: Prekhanshi Kumbhgakar

# PRN: 25070123151

# Batch: ENTC A1

# Title

Study of For Loop and While Loop in Python

# Aim

To study and implement the use of for loop and while loop in Python programming.

# Objectives

To understand the concept of iterative execution
To perform loop creation and basic iteration
To apply loop control using break and continue
To understand the difference between entry-controlled and collection-based loops
Theory

Looping is a control structure that allows a set of statements to be executed repeatedly based on a condition or over a sequence. Python provides two main types of loops: the for loop and the while loop.

1. For Loop

A for loop in Python is used for iterating over a sequence (such as a list, tuple, dictionary, set, or string). Unlike loops in other programming languages, it acts more like an iterator method. It executes a set of statements once for each item in the collection or sequence.

2. While Loop

A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The loop will continue to run as long as the condition remains true. It is primarily used when the number of iterations is not known beforehand.

Difference Between For Loop and While Loop

For loop is used when the number of iterations is known.
While loop is used when the number of iterations depends on a condition.
For loop automatically handles iteration over a sequence.
While loop requires manual updating of the loop variable.
Characteristics of Loops

Iterative: Executes code blocks repeatedly to process data structures like sets or dictionaries.
Control Flow: Manages the sequence of execution based on specific conditions or keys.
Efficiency: Reduces code redundancy by automating tasks such as removing duplicates.
Automation: Commonly used for data processing and mathematical computations.
Break Statement

The break statement is used to alter the flow of a loop by terminating the loop prematurely. When the break keyword is encountered inside a loop, the loop is immediately abandoned, and the program control resumes at the next statement following the loop. It is often used in conjunction with an if statement to exit based on a specific condition.

Continue Statement

The continue statement is used to skip the rest of the code inside the current loop block and return to the beginning of the loop for the next iteration. Unlike break, it does not terminate the loop entirely; it simply bypasses the remaining statements in the current cycle to maintain the unique flow of the loop.

For Loop: Typically used for iterating over a sequence or collection of unique elements.
While Loop: Repeats a block of code as long as a specified condition remains true.
Break Statement: Used to immediately terminate the loop and exit the current block.
Continue Statement: Used to skip the current iteration and move to the next cycle of the loop.
Applications of Loops

Data Processing: Iterating through student records or unique sets of data.
Configuration: Accessing and applying settings from dictionary-based configuration files.
Filtering: Membership testing and removing duplicate records from a collection.
Automation: Performing repetitive mathematical operations and database record updates.
Algorithms

1. Factorial of a Number

Start

Initialize loop counter i = 1 and accumulator fac = 1.

Input the target number n.

Repeat while i <= n:

Multiply fac by i.

Increment i by 1.

Print the final value of fac.

Stop

2. Reverse a Number

Start

Input the number a.

Initialize rev = 0.

Repeat while a > 0:

Find the last digit using modulo: dig = a % 10.

Update reverse: rev = (rev * 10) + dig.

Remove the last digit from a using floor division: a //= 10.

Print the reversed number rev.

Stop

3. Count Digits in a Number

Start

Input the number n.

Initialize count = 0.

Repeat while n > 0:

Increment count by 1.

Remove the last digit: n //= 10.

Print the value of count.

Stop

4. Armstrong Number

Start

Input number N as a string to easily iterate over characters.

Initialize total = 0.

Repeat for each character i in N:

Convert i to integer and raise it to the power of the length of N.

Add the result to total.

Condition Check: If total is equal to the integer value of N:

Print "It is an Armstrong Number".

Else, Print "It is not an Armstrong Number".

Stop

5. All Possible Combinations of 3 Digits

Start

Input a 3-digit number N.

Extract each digit and store them in a list d.

Use three nested loops (i, j, k) to iterate through the indices (0 to 2) of the list d.

Condition Check: Within the innermost loop, check if i, j, and k are all distinct (i != j, j != k, and k != i).

Print the combination d[i], d[j], d[k] if the condition is met.

Stop

# Conclusion

Loops provide an efficient way to handle repetitive data tasks and traverse structures like sets and dictionaries. By using break and continue, programmers gain precise control over how and when code blocks should execute or terminate, making them essential for real-world applications.
