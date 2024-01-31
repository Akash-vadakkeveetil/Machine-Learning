

> This repo consists of all the important and basic topics of python to get started with python

```PYTHON
print("Hello world")

```
This is the basic print function
- #- for single line comment
- ''' content here''' - for multi line comment

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
for i in a:
    print(i)
```

- String accessing
```PYTHON
text = "Hello"
print(text[0])# prints the zeroth character
print(text[2:4])# print values in between 2 and 4 place
print(len(text))#Print length of the string
```

## Operators in Python

- ** operator -> 2**3 = 2^3
print ( 2**3) - answer will be 8

- floor divider (//)
print(10//3) - removes decimel

- arithmetic operator - +,-,*,/,%

- comparison - = =,!=,>,<,>=.........

- logical - and, or, not

## Functions in Python

```PYTHON
def msg():#fucnton definition
    print("Hello")
msg() # function call
```

- A basic program using Functions with arguments passed
```PYTHON
def add(num1,num2):
    print(num1+num2)

a = int(input("Enter first number\n"))
b = int(input("Enter second number\n"))

add(a,b)
```

## Python collection datatypes

- Mainly 4 Types , they are :
1. List
2. Tuple
3. Set
4. Dictionary

## List

- LIST - a single variable with many values , we can hold different types of data such as strings, integers etc

```PYTHON
list_name = ["carrot","round carrot","apple",1,2]
print(len(list_name))# number of elements
print(list_name[3])# prints apple
list[1] = "orange"# updates the value of postion 1 in list
```

## Tuple

- value cannot be updated
- we use ( ) round bracket itself and not[ ]
```PYTHON
tuple = ("carrot","round carrot",1,2)
print(tuple)
# error tuple[1] = "orange"
```

## Set

- SET = {}
- no order hence it will be unordered and hence cannot be accessed
```PYTHON
setname = {"apple","orange",1,2}
print(setname)

#to check whether a value is inside the set or not
print("apple" in setname)

#to add a value in set
setname.add("beetroot")

#to update , that is to add multiple value
setname.update(["beetroot","cabage"])

# to remove
setname.remove("cabage")

# to discard one
setname.discard("apple")
```

## Dictionary 

- Values are arranged in key value pairs
- word = meaning similarly key = value
```PYTHON
dict1 = {
    "name":"Ronaldo",
    "age":52,
    "place":"saudi",
    "home":"Real madrid",
    "status":"One of GOAT"
    }

print(dict1)
print(dict1["name"])  # Output: Ronaldo
print(dict1["age"])   # Output: 52

# add a new key value pair
dict1["team"] = "Juventus"
print(dict1)
# Output: {'name': 'Ronaldo', 'age': 52, 'place': 'saudi', 'home': 'Real madrid', 'status': 'One of GOAT', 'team': 'Juventus'}


#Update a valuedict1["age"] = 36
print(dict1)
# Output: {'name': 'Ronaldo', 'age': 36, 'place': 'saudi', 'home': 'Real madrid', 'status': 'One of GOAT'}


# Removing a key-value pair
del dict1["place"]
print(dict1)
# Output: {'name': 'Ronaldo', 'age': 36, 'home': 'Real madrid', 'status': 'One of GOAT'}

```

