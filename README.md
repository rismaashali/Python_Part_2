# Python (Part 2)
# Operation in List, Set, and String
## len()
- The len() function returns the number of items in an object. When the object is a string, the len() function returns the number of characters in the string.

## min () and max.
- The min() function returns the item with the lowest value, or the item with the lowest value in an iterable. If the values are strings, an alphabetically comparison is done.
- The max() function returns the item with the highest value, or the item with the highest value in an iterable. If the values are strings, an alphabetically comparison is done.

## count ()
- The count() method returns the number of elements with the specified value or the number of times a specified value appears in the string.

## Merging (+) dan Replication (*)
- To concatenate, or combine, two strings you can use the + operator.
- To double or more strings, you can use the * operator.

## Range()
- The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

## In and Not In
- When used in a condition, the statement returns a Boolean result evaluating into either True or False. When the specified value is found inside the sequence, the statement returns True. Whereas when it is not found, we get a False.

## Giving value in multiple variable
- Python has the best practical way. We can give values in multiple variables from list and tuple elements. The amount of variable and item must have same amount and we can change two or more variables

## Sort List
- Ascending : _sort()_ method that will sort the list ascending, by default.
- Descending : To sort descending, use the keyword argument _reverse = True_.
- Case insensitive : _sort()_ method is case sensitive, resulting in all capital letters being sorted before lower case letters. Use _str.lower_ as a key function to sort by the first letter.

# Operator, Operands, and Expressions
## Arithmetic Operators
- (+) Addition
- (-) Subtraction
- (*) Multiplication
- (**) Power
- (/) Division
- (//) Floor division
- (%) Modulus

## Comparison Operators
- (==) Equal
- (!=) Not equal
- (>) Grater than
- (<) Less than
- (>=) Greater than or equal to
- (<=) Less than or equal to

## Boolean Operators
- AND : returns True if both statements are true.
- OR : Returns True if one of the statements is true.
- NOT : Reverse the result, returns False if the result is true.

## Assignment Operators
Assignment operators are used to assign values to variables
- += : x +=3 same as x = x + 3
- -= : x -=3 same as x = x - 3
- *= : x *=3 same as x = x * 3
- **= : x **=3 same as x = x ** 3
- /= : x /=3 same as x = x / 3
- //= : x //=3 same as x = x // 3
- %= : x %=3 same as x = x % 3

# Conditional Expression
## if statement 
- if statement is conditional statement to decides whether certain statements need to be executed or not. It checks for a given condition, if the condition is true, then the set of code present inside the ” if ” block will be executed otherwise not.
## else statement
- Else statement block will execute only when the if condition becomes false. It is the block where you will perform some actions when the condition is not true.
## elif statement 
- Elif statement is used to check multiple conditions only if the given condition is false. It’s similar to an else statement and the only difference is that in “else” we will not check the condition but in “elif” we will check the condition.

# For and While Loop
## For Loop
- For loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.
## Nested for loop
- A nested for loop is a for loop inside a for loop.
The "inner loop" will be executed one time for each iteration of the "outer loop":
## If inside for loop
- Inside a for loop, you can use if statements as well.
to execute program if expression is true
## Else After For
- The else function after for takes precedence on a repeat of a search nature, to provide a way out of the program when the search is not found.

## While
- "While" on python is used to execute statements as long as the given condition is met (True)
- The condition can be any expression, please remember that True in Python includes all non-zero values
- When the condition becomes false, the program will proceed to the line after the statement block

## Break
- The break statement in Python terminates the current loop and resumes execution at the next statement.
- If you have a tiered loop, the break will stop the loop according to the level or the loop where it is located
- However, if it is placed for example in a loop with a second depth, then only stops is that loop, not with the main loop

## Continue
- A continue statement will make the current iteration stop, then move on to the next iteration.
- The output will ignore statements that are between continue to the end of the looping block

## Pass
- This control is widely used when we have not implemented or prepared a place for implementation, as well as leaving the program running when experiencing errors or exceptions.
- Pass statement is an operation of null (empty), nothing happens when it is called

# List Comprehension
- List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list.

# Error Handling
## Syntax Errors
- Python doesn't understand of the command
- Usually happens when you start studying
- Improper indent placement

## Exceptions
- Even if the statement or expression from Python is correct, it is possible that an error may occur when executing
- Errors during the process are called "Exceptions", and if left unchecked, they can have bad consequences
- Most exceptions cannot be handled by the application, so the application crashes and an error appears
