# Python

## WEEK-1
# Variable
- Python has multiple types of variables: strings are collections of characters; floats are decimal numbers; complex numbers are utilized in intricate mathematical computations; and integers are whole numbers.
- Changeables
Data values are kept in containers called variables.

Establishing Variables
There isn't a command in Python for declaring variables.

The instant you give a variable a value for the first time, it is formed.
> Python has no additional commands to declare a variable. As soon as the value is assigned to it, the variable is declared.
* x=10
  > Varaible is declared as the value 10 is assigned to it.
  # Data structure
  > Unlike a list, a set's elemental order is irrelevant. Lists and tuples are similar in that once they are declared, they cannot be changed. They are helpful for efficiently storing vast amounts of data in memory, such as pairs of X and Y coordinates. And last, just like a word and its meaning in a book, a dictionary is an assortment of key-value pairs. Curly braces are used to declare dictionaries, and keys are used to access them.
  ## Operator
  Division can be performed using the forward slash operator, and it returns a floating-point value, even if the result is a whole number. The modulus operator is specific to programming and provides the remainder after division. For instance, when 20 is divided by 6, the remainder is 2, so the modulus operator will return 2. This operator is frequently used in programming and has various applications.

Strings can also be manipulated using operators. The addition operator can concatenate or combine two strings together, while the multiplication operator can repeat a string a certain number of times. It's important to note that the addition operator for strings works only with two strings, while the multiplication operator can work with either a string or a number.

Comparison operators, logical operators, identity operators, and membership operators are another set of operators in Python. Comparison operators evaluate two variables or values and produce a Boolean result, either true or false. Examples include the double equal sign for equality, less-than, less-than or equal to, greater than, and greater than or equal to.

Logical operators, such as "and," "or," and "not," operate on Boolean values. The "and" operator returns true only if both operands are true, while the "or" operator returns true if at least one operand is true. The "not" operator negates the Boolean value it operates on.

Membership operators, "in" and "not in," are used to check whether a value is present in a sequence or not. For instance, using "in" can check if a number or a string exists in a given list or string.

# Control flow 
> One of the three primary control flow types in programming is the if statement, which lets you run a block of code only in response to specific conditions being met. The if statement in Python looks like this: "a = True, if a: print It is true." The code that is indented beneath the if statement will be executed if the condition is true. By indenting it deeper, you can put further code behind the if expression. If you include an else statement, if the condition is false, the code under it will be run.

> Python indentation plays a crucial role in defining the organization of your program. A list or any other iterable object can be iterated over using a for loop. This is how a for loop is written in Python: "for item in my_list: print item." 

You may give the item in the for loop any name you choose; it's merely a variable that indicates the item in the list that's currently selected. Similar to a for loop, a while loop doesn't stop until a predetermined condition is met. In Python, a while loop can be used in the following manner: "a = 0, while a < 5: print a, a = a + 1." Ensuring that the while loop's condition will eventually become false is crucial; otherwise,

> The "def" keyword in Python, together with the function name and parameters enclosed in parenthesis, can be used to define a function. The code that applies the required action to the inputs is contained in the function body, which is indented. The output is specified by the use of the "return" keyword. Functions may or may not return a value, and they may accept one or more arguments. 

A function might, for instance, change a variable without giving back any information. One method that publishes output to the console but does not return anything is the print function. When a function does not explicitly return anything, the unique Python keyword "None" is used to indicate the absence of value.
> We have worked with functions a lot in the Python course. Indeed, in our first Python program, the message "Hello World" was displayed using the print function. 

A common analogy in beginning programming courses is that programming is like making a cake: you follow the directions step-by-step, and the end product is a cake. At its most basic, this analogy makes sense, but programming is far more intricate than that. Systems, tasks, objects, and interacting components are all part of programs. Therefore, rather than just following a set of linear instructions, programmers need to think in terms of constructing programs.

> The parameters and name of a function are indicated by the def statement. Thus, let's build a function called performOperation and pass it operation, num1, and num2 as parameters. Our objective is to create a basic function that accepts two numbers as input, performs an action (either "multiply" or "sum"), and outputs the result. Should the operation be set to "multiply," the function must return the product of num1 and num2, and if set to "sum," it must return the sum of num1 and num2.

> The function performOperation, for instance, can be called with two parameters, 2 and 3, and the operation "sum." Five is the anticipated outcome.

But having to type "sum" as the operation parameter each time we call the function can get tiresome. In order to resolve this, we can use name parameters or keyword arguments to set the operation parameter to a default value. Let's descend the code and make "sum" the operation's default value.

> We will have five in total if we take this bit out. We are able to assign our own value, though. To override it, we use "operation equals multiply". It is not necessary to explicitly say "operation equals multiply" when calling this function. Alternatively, "multiply" can be passed in as the third parameter.


