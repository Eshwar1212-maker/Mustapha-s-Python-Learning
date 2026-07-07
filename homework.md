## Python Resources

Download Python: https://www.python.org/downloads/

Download VS Code: https://code.visualstudio.com/download?_exp_download=d53503e735

W3Schools Python: https://www.w3schools.com/python/

Free Book (Automate the Boring Stuff): https://automatetheboringstuff.com/

Visualize your code: https://pythontutor.com/

Run Python in browser: https://replit.com/

# Homework for July

## Task 1 — Hello, World! 
**Topic:** Print Statements

Write a program that prints these 3 lines:
```
Hello, World!
My name is [Your Name]
I am learning Python!
```
> 💡 **Bonus:** Print your name 5 times using only ONE line of code. Hint: look up string repetition with `*`

---

## Task 2 — Variables & Data Types 
**Topic:** Strings, Integers, Floats, Booleans | 
Create variables storing your **name**, **age**, **height**, and whether you're a **student (True/False)**. Print each one with a label, then use `type()` to print the data type of each variable.

> 💡 **Bonus:** Combine your name and age into one sentence using an f-string: `f"My name is {name} and I am {age} years old"`

---

## Task 3 — Basic Math & User Input 
**Topic:** Arithmetic, `input()` 

Ask the user for two numbers. Print the result of **addition, subtraction, multiplication, and division** between them.

> 💡 **Bonus:** Also calculate floor division `//` and modulus `%` — research what they do!

References:

-https://realpython.com/python-input-output/


## Task 4 — If/Else Decisions 🚦
**Topic:** Conditionals | 


Ask the user for their age. Print:
- `"You are a minor."` → under 18
- `"You are an adult."` → 18 to 64
- `"You are a senior."` → 65 and above

> 💡 **Bonus:** If they enter a negative number, print `"Invalid age entered."`

---

## Task 5 — For Loops 🔄
**Topic:** `for`, `range()` | 

Use a loop to print the **multiplication table for 7** (7x1 through 7x10), formatted like:
```
7 x 1 = 7
7 x 2 = 14
...
```
> 💡 **Bonus:** Ask the user which times table they want, then print it for them.

References:

- https://realpython.com/python-for-loop/
---

## Task 6 — Lists 📋
**Topic:** Lists, indexing, list methods 

Create a list of 5 favorite foods. Then:
- Print the first and last item using indexing
- Add a new food with `.append()`
- Remove one food with `.remove()`
- Print the final list and its length with `len()`

> 💡 **Bonus:** Loop through the list and print each item numbered. Example: `1. Pizza`

References:

-https://www.w3schools.com/python/python_ref_list.asp

---

## Task 7 — Functions 🔧
**Topic:** `def`, parameters, return values

Write two functions:
1. `greet(name)` → prints `"Hello, [name]! Welcome to Python."`
2. `add_numbers(a, b)` → returns the sum of two numbers

Call each function and print the results.

> 💡 **Bonus:** Write `is_even(number)` that returns `True` or `False`. Test it with 5 numbers.

---

## Task 8 — Dictionaries 🗂️
**Topic:** Key-value pairs

Create a dictionary with your **name, age, city, and occupation**. Then:
- Print just your name and city
- Update the city to somewhere new
- Add a `hobby` key
- Print all keys with `.keys()` and all values with `.values()`

> 💡 **Bonus:** Make a list of 3 person dictionaries and loop through, printing each person's name and age.

---

## Task 9 — File Handling 📁
**Topic:** `open()`, read, write, `with` statements

Write a program that:
1. Creates a file called `my_notes.txt` and writes 3 lines into it
2. Opens the file again and prints its contents to the console

> 💡 **Bonus:** Ask the user to type a note, then **append** it to the file using mode `'a'`

---

## Task 10 — Mini Project: Profile App 🚀
**Topic:** Everything combined 

Ask the user for their **name, age, city, and 3 hobbies**. Store everything in a dictionary, print a formatted profile, and save it to `profile.txt`.

```
===== YOUR PROFILE =====
Name:     Mustapha
Age:      25
City:     New York
Hobbies:  Reading, Coding, Gaming
========================
Profile saved successfully!
```

> 💡 **Bonus:** Wrap the whole thing in a function called `create_profile()`

---

**Good luck — you've got this! 🐍🔥**
```