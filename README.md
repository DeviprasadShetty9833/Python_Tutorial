# Python Tutorial

<br> ![Author: Deviprasad Shetty](https://img.shields.io/badge/Author-💫_Deviprasad%20Shetty-000000?style=for-the-badge&labelColor=white)
<br> 


# My Intro:
<br> Hi, 😃👋 I'm Deviprasad Shetty, highly passionate for coding, learning and exploring new fields in Computer Science domain. 
<br> I'm excited 😃 to dive deeper into my technical skills, collaborate with others, and take on projects that challenge me to grow. 
<br> Always eager to learn and connect with others who share similar interests! 🤗🧑‍💻
<br> 
| [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://linkedin.com/in/deviprasad-shetty-4bba49313) | [![Website](https://img.shields.io/badge/Website-indigo?style=for-the-badge&logo=About.me&logoColor=white)](https://yourwebsite.com/) | [![My Portfolio](https://img.shields.io/badge/My_Portfolio-000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/DeviprasadShetty9833/My_Portfolio)  |                      
|---|---|---|
<br> 

---

| [![Resources](https://img.shields.io/badge/📚_Back_to-Resources-A52A2A?style=for-the-badge&logo=book&logoColor=white)](https://github.com/DeviprasadShetty9833/Resources)  |
|---|

---


# Python_Basics

<table>
<tr><td>

<br> ![1.](https://img.shields.io/badge/_1._-Print%20a%20string%20using%20print()-34A853?style=for-the-badge&logo=python&logoColor=white)   

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python 
print("Hello World!")
```

*Output:*
```html
Hello World!
```

> - Here, print() displays the string 'Hello World!' on the console.

*Code:*
```python 
name = "Tanmay"
age = 18
branch, div = "IT", "D"
print(name, age)
print(branch)
print (div)
```

*Output:*
```html
Tanmay 18
IT
D
```

> - Here, name stores the value 'Tanmay'.
> - branch and div is stored as 'IT' & 'D' at a time.
> - 2nd & 3rd print() automatically inserts '\n' and  displays 'IT' & 'D' on the next line.

</details>


<br> ![2.](https://img.shields.io/badge/_2._-Input%20a%20string%20using%20input()-34A853?style=for-the-badge&logo=python&logoColor=white)   

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python 
name = input("Enter your name: ")
print("Hello, ", name, "! Welcome!")
```

*Output:*
```html
Enter your name: Dhanesh
Hello, Dhanesh! Welcome!
```

> - Here, input() prompts the user with "Enter your name:" and stores the input 'Dhanesh' of datatype string.
> - print() displays "Hello, Dhanesh! Welcome!" using the value of name.

 
*Code:*
```python 
x, y, z = input("Enter name, age, city: ").split()
print("Name : ", x)
print("Age : ", y)
print("City : ", z)
```

*Output:*
```html 
Enter name, age, city: Ritesh, 19, Mumbai
Name: Ritesh
Age : 19
City : Mumbai
```

> - Here, 3 inputs are taken at a time.
> - Age is taken as a string.

</details> 

<br> ![3.](https://img.shields.io/badge/_3._-Typecasting-34A853?style=for-the-badge&logo=python&logoColor=white)   

<details>
  <summary>Click to expand 🔻</summary>
  
*Code:*
```python 
n = int(input("No. of Students: "))
print(n)
```

*Output:*
```html 
No. of Students: 10
10
```

> - Here, the variable n is converted to datatype int.


*Code:*
```python 
m = float(input("Average Marks of Students: "))
print(m)
```

*Output:*
```html 
No. of Students: 75.5
75.5
```

> - Here, the variable m is converted to datatype float.


</details> 


<br> ![4.](https://img.shields.io/badge/_4._-Comments-34A853?style=for-the-badge&logo=python&logoColor=white)   

<details>
  <summary>Click to expand 🔻</summary>
  
*Code:*
```python
# This is a single-line comment.

""" This is a multi-line comment. """

''' This is a multi-line comment. '''
```
*Output:*
```html

```

> - Python ignores comments when running the code, but they help people understand what the code is doing.

</details> 

<br> ![5.](https://img.shields.io/badge/_5._-Indentation-34A853?style=for-the-badge&logo=python&logoColor=white)

<br> ⊡⁠ Indentation is used to define blocks of code.
<br> ⊡⁠ All statements with the same level of indentation are considered part of the same block.
<br> ⊡⁠ Indentation is achieved using whitespace (spaces or tabs) at the beginning of each line.
<br> <br> 

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
if 10 > 5:
    print("I have indentation.")

print("I have no indentation.")
```
> - The 1st print statement is indented by 4 spaces, so they belong to the if block.
> - The 2nd print statement is not indented, so it is outside the if block.

</details> 

</td></tr>
</table>

# Data Types

<table>
<tr><td>

<br> ![1.](https://img.shields.io/badge/_1._-Numeric-34A853?style=for-the-badge&logo=python&logoColor=white)

1.1 Integer

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
x = int(1)
print(x)
print(type(x))
```

*Output:*
```html
1
<class 'int'>
```

</details>

1.2 Float 

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
y = float(2)
print(y)
print(type(y))
```

*Output:*
```html
2.0
<class 'float'>
```

</details> 

1.3 Complex

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
z = complex(1, 2)
print(z)
print(type(z))
```

*Output:*
```html
1 + 2j
<class 'complex'>
```

</details> 

<br> ![2.](https://img.shields.io/badge/_2._-Dictionary-34A853?style=for-the-badge&logo=python&logoColor=white)

<br> ⊡⁠ Stores key-value pairs.
<br> ⊡⁠ Mutable (can be changed).
<br> ⊡⁠ No duplicate keys allowed.
<br> ⊡⁠ Maintains insertion order (Python 3.7+).
<br> ⊡⁠ No indexing, access via keys.
<br> ⊡⁠ Syntax: { "key" : "value" }

▶️ Creating a Dictionary 

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
d1 = {1 : 'Hello', 2 : 'Good', 3 : 'Morning'}
print(d1)
```

*Output:*
```html
{1 : 'Hello', 2 : 'Good', 3 : 'Morning'}
```

🔸 Using dict()

*Code:*
```python
d2 = dict(a = "Hello", b = "Good", c = 'Morning')  # String keys only
print(d2)
```

*Output:*
```html
{'a' : "Hello", 'b' : "Good", 'c' : 'Morning'}
```

🔸 Using dict() & zip()

*Code:*
```python
keys = [1, 2, 3]
values = ['Geeks', 'For', 'Geeks']
d3 = dict(zip(keys, values))
print(d3)
d3 = dict(zip(values, keys))  # Dictionaries are mutable
print(d3)

```

*Output:*
```html
{1 : 'Geeks', 2 : 'For', 3 : 'Geeks'}
{'Geeks' : 3, 'For' : 2}
```
> -  Initially, 1 is assigned to 'Geeks' then 1 is replaced and 3 is assigned to 'Geeks'.

*Code:*
```python
d4 = {'GEEKS' : 1, 'For' : 2, 'Geeks' : 3}  # Case sensitive 
print(d4)
```

*Output:*
```html
{'GEEKS' : 1, 'For' : 2, 'Geeks' : 3}
```

🔸 Storing different values

*Code:*
```python
d5 = {'name' : 'Harsh', 'age' : 19}
print(d5)
```

*Output:*
```html
{'name' : 'Harsh', 'age' : 19}
```

🔸 Storing different keys

*Code:*
```python
d6 = {"name" : 'Deva', 2025 : "year"}
print(d6)
```

*Output:*
```html
{"name" : 'Deva', 2025 : "year"}
```

</details> 

▶️ Accessing Dictionary items

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
keys = ['name', '1', (1,2)]
values = ['Deva', 'Python', (1,2,4)]

d1 = dict(zip(keys, values))
print(d1)
print(d1['name'])  # Only Keys(LHS) can be used to access items.

d2 = dict(zip(values, keys))
print(d2)
print(d2['1'])
```

*Output:*
```html
{'name' : 'Deva', '1' : 'Python', (1,2) : (1,2,4)}
Deva
{'Deva' : 'name', 'Python' : '1', (1,2,4) : (1,2)}

```

🔸 Using get()

*Code:*
```python
d = {'name' : 'Deva', 1 : 'Python', (1,2) : [1,2,4]}
print(d.get("name"))  # Only keys can be used to access items.
print(d.get(1))
print(d.get((1,2)))
```

*Output:*
```html
Deva
Python
[1,2,4]
```

</details> 

▶️ Adding & Updating Dictionary items

<details>
  <summary>Click to expand 🔻</summary>

🔸 Adding 

*Code:*
```python
d = {1 : 'Hello', '2' : 'Good', 3 : 'Morning'}
d[4] = "Deva"   # New Key-Value pair
print(d)
```

*Output:*
```html
{1 : 'Hello', '2' : 'Good', 3 : 'Morning', 4 : 'Deva'}
```

🔸 Updating 

*Code:*
```python
d = {1 : 'Hello', '2' : 'Good', 3 : 'Morning', 4 : 'Deva'}
d[3] = "Evening"   # Updating an existing value
print(d)
```

*Output:*
```html
{1 : 'Hello', '2' : 'Good', 3 : 'Evening', 4 : 'Deva'}
```

</details> 


▶️ Deleting Dictionary items

<details>
  <summary>Click to expand 🔻</summary>

🔸 Using del

*Code:*
```python
d = {1 : 'Hello', '2' : 'Good', 3 : 'Morning', 4 : 'Deva'}
del d[4]   # Deletes only Keys(LHS).
print(d)
```

*Output:*
```html
{1 : 'Hello', '2' : 'Good', 3 : 'Morning'}
```

🔸 Using pop()

*Code:*
```python
d = {1 : 'Hello', '2' : 'Good', 3 : 'Morning'}
print(d.pop('2'))  # Deletes Keys & returns its Values.
print(d)
```

*Output:*
```html
Good
{1 : 'Hello', 3 : 'Morning'}
```

🔸 Using popitem()

*Code:*
```python
d = {1 : 'Hello', 3 : 'Morning'}
K, V = d.popitem()
print(f"Key : {K}, Value : {V}")  # Deletes & returns Last Key-Value pair.
print(d)
```

*Output:*
```html
Key : 3, Value : Morning 
{1 : 'Hello'}
```

</details> 

▶️ Iterating through Dictionary items

<details>
  <summary>Click to expand 🔻</summary>
  
*Code:*
```python
d = {1 : 'Hello', '2' : 'Good', 'Morning' : 3}

for K in d.keys():
    print(f"Key : {K}")

print("\n")

for V in d.values():
    print(f"Value : {V}")
```

*Output:*
```html
Key : 1
Key : 2
Key : Morning

Value : Hello
Value : Good
Value : 3

```

*Code:*
```python
d = {1 : 'Hello', '2' : 'Good', 'Morning' : 3}

for K, V in d.items():
    print(f"Key, Value : {K}, {V}")
```

*Output:*
```html
Key, Value : 1, Hello
Key, Value : 2, Good
Key, Value : Morning, 3
```

</details> 

▶️ Nested Dictionaries

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
d = {1 : 'Welcome', 2 : 'To', 3 : {'A' : 'Harry', 'B' : 'Potter', 'C' : 'And The', 'D' : "Philosopher's", 'E' : 'Stone'}}
print(d)
```

*Output:*
```html
{1 : 'Welcome', 2 : 'To', 3 : {'A' : 'Harry', 'B' : 'Potter', 'C' : 'And The', 'D' : "Philosopher's", 'E' : 'Stone'}}
```

</details> 


<br> ![3.](https://img.shields.io/badge/_3._-Boolean-34A853?style=for-the-badge&logo=python&logoColor=white)

▶️ Boolean Examples 

<details>
  <summary>Click to expand 🔻</summary>
  
*Code:*
```python
x = {}   # empty mapping 
print(bool(x))

y = ()   # empty sequence
print(bool(y))
```

*Output:*
```html
False
False
```

*Code:*
```python
x = None
print(bool(x))

y = 0.0
print(bool(y))
```

*Output:*
```html
False
False
```

*Code:*
```python
x = 1
print(bool(x))

y = - 1.5
print(bool(y))
```

*Output:*
```html
True
True
```

*Code:*
```python
x = 'Hello'   # non empty string
print(bool(x))
```

*Output:*
```html
True
```

</details> 

▶️ Boolean Operators 

<details>
  <summary>Click to expand 🔻</summary>

🔸 OR & AND operator  

*Code:*
```python
A, B = True, False
print(A or B)   # True - If any one variable is True.
print(A and B)  # True - Iff both variables are True.
```

*Output:*
```html
True
False
```

*Logic:*

|   A   |   B   |  OR   |  AND  |
|-------|-------|-------|-------|
| True  | True  | True  | True  |
| True  | False | True  | False |
| False | True  | True  | False |
| False | False | False | False |

🔸 NOT Operator

*Code:*
```python
A, B = True, False
print(not A)   # True - If variable is False.
print(not B)
```

*Output:*
```html
False
True
```

🔸 Equivalent & Not equivalent Operator

*Code:*
```python
A, B = True, False
print(A == B)   # True - Iff both variables have same value.
print(A != B)   # True - Iff both variables don't have same value.
```

*Output:*
```html
False
True
```

🔸 is Operator

*Code:*
```python
A, B = 5, 5
print(A is B)   # True - if both variables refer to the same value in memory. 
```

*Output:*
```html
True
```

> - `==` & `is` operator work differently. `==` focuses on same values while `is` focuses on values at same Memory location.

🔸 in Operator

*Code:*
```python
fruits = ["apple", "banana", "cherry"]
print("banana" in fruits)  
print("orange" in fruits)
```

*Output:*
```html
True
False
```

> - It checks if a value exists within a sequence (like a list, tuple, string, or range).

</details> 

<br> ![4.](https://img.shields.io/badge/_4._-Set-34A853?style=for-the-badge&logo=python&logoColor=white)

<br> ⊡⁠ Stores unordered unique elements.
<br> ⊡⁠ Mutable (can add/remove items).
<br> ⊡⁠ No duplicates allowed.
<br> ⊡⁠ Unordered, so no indexing.
<br> ⊡⁠ Syntax: { item1, item2, item3 }

▶️ Creating a set

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
set1  = set(" Hello Good Morning")
print(set1)
print(type(set1))
```

*Output:*
```html
{'n', 'r', ' ', 'o', 'g', 'i', 'l', 'd', 'G', 'M', 'H', 'e'}
<class 'set'>
```

🔸 Heterogeneous Elements

*Code:*
```python
set2 = {"Hello", 10, 52.7, True}
print(set2)
```

*Output:*
```html
{'Hello', True, 10, 52.7}
```

> - Output varies as Sets display Unordered elements with No Duplicates.

</details> 

▶️ Accessing a Set 

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
set1  = set(["Hello", "Good", "Morning"])

for i in set1:
    print(i, end=" ")
```

*Output:*
```html
Morning Hello Good
```

> - Output varies

</details> 

▶️ Adding items to set

<details>
  <summary>Click to expand 🔻</summary>

🔸 Using add()

*Code:*
```python
set1 = {1,2,3,4}
set1.add(5)
print(set1)
```

*Output:*
```html
{1, 2, 3, 4, 5,}
```

> - Here, add() is used to add only a single item.

🔸 Using update()

*Code:*
```python
set2 = {1,2,3,4}
set2.update([5,6])
print(set2)
```

*Output:*
```html
{1, 2, 3, 4, 5, 6}
```

> - Here, update() is used to add multiple items.
> - Only 6 is added, bcoz 5 is already present and Set doesn't allow Duplicates.

</details> 

▶️ Removing items from a set

<details>
  <summary>Click to expand 🔻</summary>

🔸 Using remove()

*Code:*
```python
set1 = {1, 2, 3, 4, 5}
set1.remove(3)
print(set1)

set1.remove(7)
print(set1)
```

*Output:*
```html
{1, 2, 4, 5}
Traceback (most recent call last):
  File "/home/main.py", line 5, in <module>
    set1.remove(7)
    ~~~~~~~~~~~^^^
KeyError: 7
```

> - Here, remove() is used to remove only a single item.
> - It raises an error when an element is removed that does not exist.

🔸 Using discard()

*Code:*
```python
set1 = {1, 2, 3, 4, 5}
set1.discard(3)
print(set1)

set1.discard(7)
print(set1)    # No Errors raised
```

*Output:*
```html
{1, 2, 4, 5}
{1, 2, 4, 5}
```

> - Here, discard() is used to discard only a single item.
> - It doesn't raise an error when an element is discarded that does not exist.

🔸 Using pop()

*Code:*
```python
set1 = {1, 2, 3, 4, 5}
val = set1.pop()
print(val)
print(set1)
```

*Output:*
```html
{2, 3, 4, 5}
```

> - Here, pop() is used to pop & return any random item.

🔸 Using clear()

*Code:*
```python
set1 = {1, 2, 3, 4, 5}
set1.clear()
print(set1)
```

*Output:*
```html
set()
```

> - Here, pop() is used to pop all items from a set.

</details> 

🔵 Frozenset

<br> ⊡⁠ Same as a set(), but frozenset() are Immutable i.e its elements cannot be modified.
<br> ⊡⁠ It accepts iterable objects as input parameter.
<br> ⊡⁠ Syntax : frozenset(iterable_obj_name)

▶️ Converting a Dictionary to Frozenset

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
d = {"name" : "Devaratha", "age" : 19}
print(frozenset(d))
```

*Output:*
```html
frozenset({'age', 'name'})
```

<\details>

▶️ Converting a List to Frozenset

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
l = ["Hello", "Good", "Morning"]
print(frozenset(l))
```

*Output:*
```html
frozenset({'Good', 'Hello', 'Morning'})
```

<\details>

▶️ Converting a Tuple to Frozenset

<details>
  <summary>Click to expand 🔻</summary>

*Code:*
```python
t = ()   # Empty Tuple
print(frozenset(t))
```

*Output:*
```html
frozenset()
```
<\details>

<br> ![5.](https://img.shields.io/badge/_5._-Sequence-34A853?style=for-the-badge&logo=python&logoColor=white)

🔵 String

🔵 List

🔵 Tuple


</td></tr>
</table>
   

# Oops Concept 

<table>
<tr><td>

<br> ![1.](https://img.shields.io/badge/_1._-Classes_&_Objects-34A853?style=for-the-badge&logo=python&logoColor=white) 

</td></tr>
</table>

# Exception Handling 

# File Handling 

# RegEx

<table>
<tr><td>

⊡⁠ Regular Expressions (RegEx) are a powerful tool for **pattern matching** and **text manipulation** that allows you to search, extract, replace, or validate strings based on specific patterns.

**(A) `re.search()`**
- Checks if a pattern exists in a string.
- Returns the **first match** (or `None`).

*Code:*
```python
text = "Python is fun"
match = re.search(r"fun", text)
if match:
    print("Found:", match.group())  
```

*Output:*
```html
Found: fun
```

*Code:*
```python
import re
regex = r"([a-zA-Z]+) (\d+)"

match = re.search(regex, "I was born on June 2")
if match != None:
    print ("Match at index %s, %s" % (match.start(), match.end()))
    print ("Full match: %s" % (match.group(0)))
    print ("Month: %s" % (match.group(1)))
    print ("Day: %s" % (match.group(2)))

else:
    print ("The regex pattern does not match.")
```

*Output:*
```html
Match at index 14, 20
Full match: June 2
Month: June
Day: 2
```

*Explanation:*
- r"..." : Raw string to avoid escaping backslashes (i.e., \n stays as \n).
- ([a-zA-Z]+) : Match one or more letters (uppercase or lowercase). i.e., the month name.
- (\d+) : Match one or more digits i.e., the day number.
- The space '  ' between them : Expect a space between the two parts.
- match.start(), match.end() : Starting & Ending index of match in the string.
- match.group(0) : entire matched string.
- match.group(1) : 1st group of matched string.
- match.group(2) : 2nd group of matched string.

 **(B) `re.findall()`**
- Returns **all matches** as a list.

*Code:*
```python
text = "cats and dogs"
matches = re.findall(r"[a-z]+", text)
print(matches)  # Output: ['cats', 'and', 'dogs']
```

 **(C) `re.sub()`**
- Replaces matches with new text.

*Code:*
```python
text = "Python is awesome"
new_text = re.sub(r"awesome", "great", text)
print(new_text)  # Output: "Python is great"
```

 **(D) `re.split()`**
- Splits a string by a pattern.

*Code:*
```python
text = "apple,banana,cherry"
items = re.split(r",", text)
print(items)  # Output: ['apple', 'banana', 'cherry']
```

</td></tr>
</table>

# Tkinter

# Numpy

# Pandas

# Matplotlib


---


 ![status](https://img.shields.io/badge/status-upcoming-yellow)

---

| [![TOP](https://img.shields.io/badge/_🔺_-Navigate_to_TOP_↑_-blue?style=for-the-badge&labelColor=white)](#Python_Basics) | [![Resources](https://img.shields.io/badge/📚_Back_to-Resources-A52A2A?style=for-the-badge&logo=book&logoColor=white)](https://github.com/DeviprasadShetty9833/Resources) | [![My Portfolio](https://img.shields.io/badge/Back_to-My_Portfolio-000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/DeviprasadShetty9833/My_Portfolio) |
|---|---|---|
