

> This repo consists of all the important and basic topics of python to get started with python

```PYTHON
print("Hello world")

```
This is the basic print function
- #- for single line comment
- ''' <code>''' - for multi line comment

```PYTHON
a = input("Enter the number")

```
This is how we input a value to a variable we can also give output msg to the user like enter a number etc

- basic program

```PYTHON
#sum of two numbers

a = input("Enter first number\n")
b = input("Enter second number\n")
print(a+b)

# if a=5 and b =6 then output = 56 , here when we input the value it will be considered as string and hence concatination occurs , so we have to specify which is the datatype .

#sum of two numbers

a = int(input("Enter first number\n"))
b = int(input("Enter second number\n"))
print(a+b)

# This is the correct code

```
- to know the type of a variable we can use the `type` function

```PYTHON
# lets write a program to check whether a program is positive negative or zero

a = int(input("Enter the number\n"))
if a > 0:
    print("Number is positive")
elif a == 0:
    print("Number is zero")
else :
    print("Number is negative")
```
- now lets look into `while` loops
```PYTHON
# print first n numbers
a = int(input("Enter the number"))
i = 1
while i <= a:
    print(i)
    i = i + 1

```
- implement same code using for loops
```PYTHON
# print first n numbers
a = int(input("Enter the number"))
i = 1
for i in range(a+1):
    print(i)
    i = i + 1
# we give a+1 inside range if we need upto number a

```
- to print numbers between a range 
```PYTHON
start_number = 1
end_number = 10

for num in range(start_number, end_number + 1):
    print(num)

```
- print each character in a string
```PYTHON
a = "Hello"

# Using a for loop to print each character in the string
for char in a:
    print(char)

```
```PYTHON


```