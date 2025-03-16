  # assignment
  ## 1. Syntax and Semantics

**Question 1:** Write a Python program to print "Hello, World!".
Answer print("Hello,World!")

**Question 2:** Write a Python program that takes a user input and prints it.
Answer  a=input("Enter the word")
        print(a)

**Question 3:** Write a Python program to check if a number is positive, negative, or zero.
Answer number = float(input("Enter a number: "))
         if number > 0:
           print("The number is positive.")
        elif number < 0:
           print("The number is negative.")
        else:
          print("The number is zero.")

**Question 4:** Write a Python program to find the largest of three numbers.
Answer  num1 = float(input("Enter the first number: "))
        num2 = float(input("Enter the second number: "))
        num3 = float(input("Enter the third number: "))
         if(num1>=num2) and (num1>=num3):
            largest = num1
         elif (num2>=num3) and (num2>=num1):
            largest = num2
         else:
            largest = num1
         print("this is a largest number")

**Question 5:** Write a Python program to calculate the factorial of a number.
Answer def factorial(n):
       if n == 0:
        return 1
       else:
        return n * factorial(n-1)
        num = int(input("enter the number: "))
        print("this is a factorial number ")

## 2. Variables and Data Types

**Question 6:** Create variables of different data types: integer, float, string, and boolean. Print their values and types.
Answer integer_var = 23
       float_var = 1.43
       string_var = "Nitin"
       boolean_var = True

print("Integer value: {integer_var}, type: {type(integer_var)}")
print("Integer value: {float_var}, type: {type(float_var)}")
print("Integer value: {string_var}, type: {type(string_var)}")
print("Integer value: {boolean_var}, type: {type(boolean_var)}")

**Question 7:** Write a Python program to swap the values of two variables.
Answer a =6
       b = 4

print("a={a},b={b}")
a=b,b=a
print("a={a},b={b}")

**Question 8:** Write a Python program to convert Celsius to Fahrenheit.
Answer celsius =float(input("enter the temperature"))
       fahrenheit = (celsius * 9/5) +32
       print("celsius is equal to fahrenheit")

**Question 9:** Write a Python program to concatenate two strings.
Answer string1 = "Hello"
       string2 = "World"
      con_string = string1 + string2
       print("con_string")

**Question 10:** Write a Python program to check if a variable is of a specific data type.
Answer var = 10.5
       if isinstance(var, float):
         print("{var} is a float")
       else:
        print("{var} is not a float")

## 3. Basic Operators (Arithmetic, Comparison, Logical)

**Question 11:** Write a Python program to perform arithmetic operations: addition, subtraction, multiplication, and division.
Answer a = 6
      b = 2
  print("Addition: {a} + {b} = {a + b}")
  print("Subtraction: {a} - {b} = {a - b}")
  print("Multiplication: {a} * {b} = {a * b}")
  print("Division: {a} / {b} = {a / b}")

**Question 12:** Write a Python program to demonstrate comparison operators: equal to, not equal to, greater than, less than.
Answer a = 6
       b = 4
      print("{a}=={b}:{a == b}")
      print("{a} != {b}:{a != b }")
      print("{a} < {b}:{a < b}")
      print("{a} > {b}:{a > b}")

**Question 13:** Write a Python program to demonstrate logical operators: and, or, not.
Answer a = True 
       b = False
      print("True and False: {a and b}")
      print("True or False:{a or b}")
      print("not True:{not a}")

**Question 14:** Write a Python program to calculate the square of a number
Answer number = float(input("Enter the number: "))
        square = num ** 2
        print("this is a square number  ")

**Question 15:** Write a Python program to check if a number is even or odd.
Answer num = int(input("enter the number:"))
        if num % 2 == 0:
          print("it is even number")
        else:
          print("it is odd number")

**Question 16:** Write a Python program to find the sum of the first n natural numbers.
Answer n = int(input("enter a number:"))
       sum = (n * (n  + 1)) // 2
        print("the sum of natural number")

**Question 17:** Write a Python program to check if a year is a leap year.
Answer year = int(input("enter a year:"))
        if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
          print("it is a leap year")
        else:
           print("it is not a leap year")

**Question 18:** Write a Python program to reverse a string.
Answer string = input("enter a string:") 
       reversed_str = string [::-1]
       print("this is a reversed_str")

**Question 19:** Write a Python program to check if a string is a palindrome.
Answer string = input("enter a string:")
        if string == string[::-1]:
          print("{string} it is a palindrome.")
        else:
           print("{string}it is not a palindrome")

**Question 20:** Write a Python program to sort a list of numbers in ascending order.
Answer  number = [int (x) for x in input("enter number separated by space: ").split()]
         number.sort()
           print("it is a sorted list")
