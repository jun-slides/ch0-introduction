---
theme: seriph
title: Python Basics - Chapter 2
layout: cover
class: text-center
drawings:
  persist: false
---

# Introduction

---
layout: quote
---

# 🌱 Section 1: Foundations

<v-clicks>

- **🔤 Chapter 1: Strings and Variables**
- **🔢 Chapter 2: Types, Numbers and Calculations**
- **🔀 Chapter 3: Making Decisions**
- **🧠 Chapter 4: Logic and Nesting**

</v-clicks>


---
layout: quote
---

# 🔁 Section 2: Collections and Loops

<v-clicks>

- **📋 Chapter 5: Lists**
- **🔄 Chapter 6: For Loops**
- **⏳ Chapter 7: While Loops**


</v-clicks>


---
layout: quote
---

# 🧰 Section 3: Functions and Data

<v-clicks>

- **⚙️ Chapter 8: Functions**
- **📖 Chapter 9: Dictionaries**
- **🎮 Projects**


</v-clicks>

---
layout: quote
---


# Projects
- **Rock paper Scissors**
- **Random Password Generator**
- **Math Quiz Game**
- **Tic Tac Toe**
- **Hangman**


---
layout: quote
---

# Rock Paper Scissors
Fair version

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/5af2874f46d6?outputOnly=true&start=result&runOption=run"
    class="w-full h-100 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>


---
layout: quote
---

# Rock Paper Scissors
Unfair version (the computer always wins)

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/806b76ae5aca?outputOnly=true&start=result&runOption=run"
    class="w-full h-100 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>

---
layout: quote
---

# Random Password Generator

<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/6615e9c21a2e?outputOnly=true&start=result&runOption=run"
    class="w-full h-100 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>

---
layout: quote
---

# Math Quiz Game
<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/85a664f59835?outputOnly=true&start=result&runOption=run"
    class="w-full h-100 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>


---
layout: quote
---

# Tic Tac Toe
<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/412c58e1e464?outputOnly=true&start=result&runOption=run"
    class="w-full h-100 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>



---
layout: quote
---

# Hangman
<div v-click>
  <iframe
    v-if="$clicks >= 1"
    src="https://trinket.strivemath.org/embed/python3/a545993e2d40?outputOnly=true&start=result&runOption=run"
    class="w-full h-100 rounded-lg border border-gray-500/40 mt-6"
  ></iframe>
</div>




---
layout: quote
---

# 🚀 Section 4: Real-World Skills

<v-clicks>

- **📁 Chapter 10: Working with Files**
- **🛡️ Chapter 11: Exception Handling**
- **🏗️ Chapter 12: Object-Oriented Programming**


</v-clicks>


---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 1: Strings and Variables 🔤
- Print text, add comments, and store data in variables
- Mix variables and text with f-strings
- Get user input with `input()`
- Transform text with `len()`, `.upper()`, `.lower()`, `.title()`, `.replace()`
- Pick out characters with `[]` and follow naming rules

---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 2: Types, Numbers and Calculations 🔢
- Tell apart `str`, `int`, and `float`, and convert between them
- Do math with `+ - * / // % **` and use PEMDAS
- Fix errors from mixing text and numbers
- Format decimals (`:.2f`) and use `round()`, `min()`, `max()`
- Handle quotes and escape characters like `\n`

---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 3: Making Decisions 🔀
- Write `if` / `elif` / `else` statements
- Use `True` / `False` and comparison operators

---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 4: Logic and Nesting 🧠
- Combine conditions with `and`, `or`, `not`
- Choose between multiple `if`s and `if/elif/else`
- Write nested `if` statements
- Clean up messy input with `.lower()` and `.strip()`
- Use truthy and falsy values

---
layout: quote
---

#### 🔁 Section 2: Collections and Loops

<br> 

# Chapter 5: Lists 📋
- Generate random numbers with `random`
- Create, access, change, add, and remove list items
- Slice, sort, reverse, search, and count
- Copy lists safely

---
layout: quote
---

#### 🔁 Section 2: Collections and Loops

<br> 

# Chapter 6: For Loops 🔄
- Loop through lists and strings, and repeat with `range()`
- Filter and process data by combining loops with `if`
- Build new lists, including list comprehensions
- Use `split` / `join`, tuples, and nested loops

---
layout: quote
---

#### 🔁 Section 2: Collections and Loops

<br> 

# Chapter 7: While Loops ⏳
- Repeat until a condition is met, using conditions, flags, `break`, and `continue`
- Validate user input
- Choose between `while` and `for`

---
layout: quote
---

#### 🧰 Section 3: Functions and Data

<br> 

# Chapter 8: Functions ⚙️
- Create functions with parameters, defaults, and `return`
- Use positional and keyword arguments
- Understand variable scope
- Import code with `import`, `as`, and `from ... import`

---
layout: quote
---

#### 🧰 Section 3: Functions and Data

<br> 

# Chapter 9: Dictionaries 📖
- Store, read, update, and delete key-value pairs
- Loop through dictionaries and use `.get()` for safe lookups
- Work with nested dictionaries and lists of dictionaries
- Write dictionary comprehensions and ternary expressions

---
layout: quote
---

#### 🧰 Section 3: Functions and Data

<br> 

# Projects 🎮
- Build full programs: Fruit Machine, Hangman, Cho-Han, Bagels, Tic-Tac-Toe, Coffee Machine, Blackjack

---
layout: quote
---

#### 🚀 Section 4: Real-World Skills

<br> 

# Chapter 10: Working with Files 📁
- Read, write, and append files
- Use `with` to close files safely
- Save and load structured data with JSON

---
layout: quote
---

#### 🚀 Section 4: Real-World Skills

<br> 

# Chapter 11: Exception Handling 🛡️
- Handle errors with `try` / `except` / `else` / `finally`
- Catch specific error types and print error messages
- Write retry loops for bad input

---
layout: quote
---

#### 🚀 Section 4: Real-World Skills

<br> 

# Chapter 12: Object-Oriented Programming 🏗️
- Create classes and objects
- Store data in attributes and set it up with `__init__()`
- Write methods with `self`
- Build programs with multiple objects