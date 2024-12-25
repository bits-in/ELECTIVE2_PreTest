1. Introduction to Variables
1.1) What will be the type of the add variable?
a = 10

b = 5.1

add = a + b

a = 10

b = 5.1

add = a + b
type(add)
float

```diff
+ Correct!
```

1.2) Is 5 = (3+2)?
x = (3+2)
print(x)
print(x==5)
## answer
#YES
5
True

```diff
+ Correct!
```

1.3) Add 33 in variable a and print the result
a = 3

a = 3
b = 33
c = a + b

print(c)
36

```diff
+ Correct!
```

1.4) Convert integer variable a to float and check its type
a = 3

a =3
print(float(a))
type(a)
3.0
int

```diff
+ Correct!
```

2. Collection of Variables
2.1) Create a list of repeated element (element 2,48 times)
a = ([2] * 48)
print(a)
[2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2, 2]

```diff
- Wrong.
```

2.2) Replace the second element of the list with "strawberries"
list = ["apple","orange","grapes","watermelon"]

list = ["apple","orange","grapes","watermelon"]
a = "strawberries"

list = ["apple",a,"grapes","watermelon"]
print(list)
['apple', 'strawberries', 'grapes', 'watermelon']

```diff
+ Correct!
```

2.3) Check length of list
List1 =["a","b","c","d","e"]

List1 =["a","b","c","d","e"]
print(len(List1))
5

```diff
+ Correct!
```

2.4) Create a dictionary with the following information:
brand = Audi

Model = Q2

Year = 1980

Book = {
    "brand": "Audi",
    "Model": "Q2",
    "Year": "1980"
}
print(Book)
{'brand': 'Audi', 'Model': 'Q2', 'Year': '1980'}

```diff
+ Correct!
```

2.5) Create a set of following elements
1.0, "Hello", 55 , (6,7,8)

elements = {1.0,"Hello",55,(6,7,8)}
print(elements)
{1.0, (6, 7, 8), 'Hello', 55}

```diff
+ Correct!
```

3. Data Types and String Manipulation
3.1) Printing your name My_Name = "My name is Jupyter!" Also, check if My_Name is all Caps or not. Use isupper() to check returns True if all the letters are Capitals, False if atleast one letter in in lower case.
HINT: My_Name.isupper()

My_Name = "My name is Jupyter!"
My_Name.isupper()
False

```diff
+ Correct!
```

3.2) Convert My_Name to all caps. Hint: My_Name.upper().
My_Name = "My name is Jupyter!"
print(My_Name.upper())
MY NAME IS JUPYTER!

```diff
+ Correct!
```

3.3) if int1 = "500", what is the Datatype of int1
int1 = "500"
type(int1)
str

```diff
+ Correct!
```

4. Practice Exercise on Conditional Statement
4.1) if x = 20 and y = 30. Write a python code to check if x is less than y.
x = 20
y = 30

if (x < y):
    print("x is less than y")
else:
    print("x is greater than y")
x is less than y

```diff
+ Correct!
```

4.2) Check if a is equal to 10, If yes, print "Hello", else print "Good Bye"
a = 56

a = 56
if (a == 10):
    print("Hello")
else:
    print("Good Bye")
Good Bye

```diff
+ Correct!
```

4.3) Check whether a number is even or odd
a = 2020

a = 2021

if a % 2 == 0:
    print(f"{a} is even")
else:
    print(f"{a} is odd")
2021 is odd

```diff
+ Correct!
```

4.4) Check if the word "Data" is present in the sentence "I am a Data Scientist". If found, print "It is present" else print FALSE.
sentence = "I am a Data Scientist"
if "Data" in sentence:
    print("Data is present")
else:
    print("FALSE")
It is present

```diff
+ Correct!
```

4.5) Write python code to check if a number is positive or negative.
a = int(input('Enter a number(+/-):'))

if (a >= 0):
    print(f"{a} is positive")
else:
    print(f"{a} is negative")
0 is positive

```diff
- Wrong.
```

5. Practice Exercise on Loops
5.1) Print Data Science 5 times using for loop
for a in range(5):
    print("Data Science")
Data Science
Data Science
Data Science
Data Science
Data Science
Note: Remember to keep the index as one more than what is required. In the above code the indexing is done from 0 to 5 which are 6 places but Python has printed it 5 times.

```diff
+ Correct!
```

5.2) Print all the even numbers from 1 to 20 (both inclusive) using for loop.
for a in range(1,21):
    if (a % 2 == 0):
        print(a)
2
4
6
8
10
12
14
16
18
20

```diff
+ Correct!
```

6. Function
6.1) Define the python function to check whether the number 33 is even or odd
def even_odd():
    number = 33
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"

oddeven = even_odd()
print(oddeven)
Odd

```diff
- Wrong.
```
 
6.2)Write the python program to get the unique values from the given list
 
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
Cell In[87], line 6
      3     return unique_values
      5 input_list = [1, 2, 2, 3, 4, 4, 5, 6, 6, 7]
----> 6 unique_values = get_unique_values(input_list)
      7 print("Unique values:", unique_values)

Cell In[87], line 2, in get_unique_values(input_list)
      1 def get_unique_values(input_list):
----> 2     unique_values = list(set(input_list))  # Convert list to set to remove duplicates, then back to list
      3     return unique_values

TypeError: 'list' object is not callable
 
6.3) Define the python function which adds two global numeric variables (1204 and 344536) Without Argument.
x = 1204
y = 344536

def z():
    return x+y

result = z()
print(result)
345740

```diff
+ Correct!
```

```diff
! 18/21
```
