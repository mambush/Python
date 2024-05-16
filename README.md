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

## Functions

> The "def" keyword in Python, together with the function name and parameters enclosed in parenthesis, can be used to define a function. The code that applies the required action to the inputs is contained in the function body, which is indented. The output is specified by the use of the "return" keyword. Functions may or may not return a value, and they may accept one or more arguments. 

A function might, for instance, change a variable without giving back any information. One method that publishes output to the console but does not return anything is the print function. When a function does not explicitly return anything, the unique Python keyword "None" is used to indicate the absence of value.
> We have worked with functions a lot in the Python course. Indeed, in our first Python program, the message "Hello World" was displayed using the print function. 

A common analogy in beginning programming courses is that programming is like making a cake: you follow the directions step-by-step, and the end product is a cake. At its most basic, this analogy makes sense, but programming is far more intricate than that. Systems, tasks, objects, and interacting components are all part of programs. Therefore, rather than just following a set of linear instructions, programmers need to think in terms of constructing programs.

> The parameters and name of a function are indicated by the def statement. Thus, let's build a function called performOperation and pass it operation, num1, and num2 as parameters. Our objective is to create a basic function that accepts two numbers as input, performs an action (either "multiply" or "sum"), and outputs the result. Should the operation be set to "multiply," the function must return the product of num1 and num2, and if set to "sum," it must return the sum of num1 and num2.

> The function performOperation, for instance, can be called with two parameters, 2 and 3, and the operation "sum." Five is the anticipated outcome.

But having to type "sum" as the operation parameter each time we call the function can get tiresome. In order to resolve this, we can use name parameters or keyword arguments to set the operation parameter to a default value. Let's descend the code and make "sum" the operation's default value.

> We will have five in total if we take this bit out. We are able to assign our own value, though. To override it, we use "operation equals multiply". It is not necessary to explicitly say "operation equals multiply" when calling this function. Alternatively, "multiply" can be passed in as the third parameter.

## NB:
A function is a block of code which only runs when it is called.
> You can pass data, known as parameters, into a function.
> A function can return data as a result.

# Creating A function
> In Python a function is defined using the "def" keyword:

# Example:
> def my-function():
 print("Hello from a function")

# Calling a function 
> To call a function, use the function name followed by Paranthesis:
# Example:
> def my-function():
  print("Hello from function")
  my-function()

# Arguments
> Information can be passed into functions as arguments.
> Arguments are specified after the function name, inside the Parentheses.
> You can add as many arguments as you want, just separate them with a comma.

# Example:
> def my-function(fname):
   print("fname +Refsness")
my-function("Emil")
my-function("Tobias")
my-function("Linus")

> Arguments are often shortened to "args" in python documentations.

# Parameters or Arguments
> The term parameter and arguments can be used for the same thing: Information that are passed int a function.

Paramaters or Arguments the term parameter and arguments can be used for the same thing:
Information that are passed into a function.

> From a function's perspective:
* A parameter is the variable listed inside the paretheses in the function definition.
* An argument is the value that is sent to the function when it is called.
  # Number of Arguments
  > By default, a function must be called with the correct number of arguments. Meaning that if your function experts 2 arguments, you have to call the function with 2 arguments, not more, and not less.
  ## Example:
  > This function experts 2 arguments, and gets 2 arguments:
   def my-function(fname, 1name):
     print(fname +"" + 1name)
  my-function("Emil","Refsnes")
  > If you try to call the function with 1 or 3 arguments, you will getan error.
  # Example:
  This function experts 2 Arguments, but gets only 1:
   def my-function(fname, 1name):
     print(fname + ""+ 1 name)
  my-function("Emil")

  # classes and Objects

  As a classic example to demonstrate classes in programming, we can create a class called Dog, as it has multiple functions and attributes, such as legs, a name and bark. When we define a class, we can use an uppercase letter for the class name, and we start defining all the functions and attributes inside the class definition.
  ## Anatomy of a class
  > Class topics are often dense and difficult to comprehend. It's possible we have no idea what they are or how to figure out which class a member is in. In spite of this ambiguity, consider the dog class as an illustration of a previously established class. Name and legs are the two instance attributes of this class, which are shared by all instances of the dog class. "my_dog.name" and "my_dog.legs," respectively, allow us to output the name and legs of a newly created instance, such "Rover," when we create one.
> We cannot directly see the value of the legs attribute, even though it is hardcoded in the dog initialization function. If we try to access "dog.legs," we will get an error, and we cannot modify the value of legs.
> So, we may ask ourselves, is having four legs an inherent property of being a dog? Even though three-legged dogs are adorable, we can create a class for them as well.
## Static attributes
> Modify the class's handling of the legs attribute for the time being. Declare it as a static variable outside of the constructor rather than retaining it in the constructor. This implies that the value of legs will be the same for every instance of the class. Calling dog will allow you to directly access the legs attribute on the class itself dog.>-gs. These variables are often used to hold constants or essential business logic, and they are referred to as "static" variables since they remain the same for every iteration.
# Example:
> class Dog:
   legs=4
   def_init_(self, name):
    self.name= name

   def speak(self):
    print(self.name +'says:Bark!')
    myDog = Dog('Rover')
     print(myDog.name)
     print(myDog.legs)

     output = Rover
            = 4
    In [4] = Dog.legs
    out[4] = 4
    In [5] = Dog.legs = 3

    In [6] = myDog = Dog('Rover')
             print(myDog.name)
             print(myDog.legs)
    output = Rover
           = 3
 
>  ## NB:It is important to note that static variables can still be changed, so to prevent this, programmers conventionally add an underscore before the variable name. This indicates that the variable should not be modified directly, and a getter method should be used instead.
> A getter method retrieves the value of the variable, and in this case, it would be >-t<-gs . However, this does not actually need to pass in the "self" attribute for this method, because legs is a static variable in the class. Call the method in the traditional way, without passing in "self" , but it is also possible to call it with "self" included.

  ## Instance and Static Methods
  One of your favorite things to do in Python may be string parsing. To demonstrate, create a class called Word Set that contains a set of words. 

> Start with an empty set and add to it by passing in big blocks of text, punctuation and all. 
> Add text using the method add text, which first calls the method clean text to remove the punctuation and make everything lowercase. 
> Then use the split function to turn the sentence into a list of words, which can be added to the set. 
> Finally, print the set of words.
In[4]: class wordSet:
       def_init_(self):
       Self.words = set()

  def addText(Self, text):
      text = wordSet.cleanText(text)
      for word in text.Solit():
      Self.words.adds(word)

      def cleanText(text):
      # chaining functions
      text = text.replace( 'I','').replace(',','').replace(',','').replace('\','')
      return text.lower()
    wordSet = wordSet[]

    wordSet.addText('Hi,I\m Ryan! Here is a sentence I want to add!')
    wordSet.addText('Here is another sentence I want to add.')

    print(wordSet.words)

    {'a','add','another','is','to','hi','Sentence','here','want','i','ryan','Im'}
    > While add text is an instance method that is associated with a certain class instance, clear text is a static method that does not belong to any specific class instance. To customize which punctuations are changed, one can also add static variables such as replace puncs. Static variables can be referred to either the class name or the class instance; instance methods cannot be used for this purpose.
 ## Class Inheritance
 > One class may inherit every method and attribute of another class in the domain of computer science and Python programming. The new class that builds upon the original is called the child class, while the original class is called the parent class. When a child class is formed, this inheritance procedure is automatically initiated.
> Look at the example: there is a dog class and a chihuahua class needs to be created that inherits from the dog class. To do this, simply write "class Chihuahua(dog):" and include "pass" for now, which creates the new class. A chihuahua instance can then be created using all the methods and attributes of the parent dog class.
# Example:
> class Dog:
   _legs = 4
  def_init_(Self,name):
  self.name = name

  def speak(self):
  print(Self.name +'Says:Bark!')

  def getLegs(Self):
     return self_legs

     class chihuahua(Dog):
          def speak(Self):
          print(f"(self.name)says:yap yap yap!")

          defwagTail(Self):
             print("Vigorous wagging!")

             dog = chihuahua('Roxy')
             dog.speak()
             dog.wagTail()

             Roxy says: yap yap yap!
             vigorous wagging!

             myDog=Dog("Rover")
             myDog.speak()

             Rover says: Bark!
## NB:However, if the child class defines an attribute or method that is the same as the parent class, the child's version will overwrite the parent's version.
> In this example, overwrite the dog class's "speak" method with a more appropriate "yap, yap, yap" method for chihuahuas. You can also add new methods to the child class, like a "wag tail" method, which the chihuahua can use. This is useful when an existing class is used but needs a few changes or additions to it.
## Extending Built-in Classes:
> We can also apply class extensions in Python's built-in classes. In Python, creating a new list can be done by instantiating it as "list". Although it appears as a function, "list" is actually a class.


