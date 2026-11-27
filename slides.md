---
theme: seriph
title: Python Basics - Chapter 0
layout: cover
class: text-center
drawings:
  persist: false
---

# Chapter 0: Introduction

<div class="opacity-60 mt-8">
syllabus overview · projects · program setup
</div>

---
layout: quote
---

# Modules

<v-clicks>

# <span class="emoji">🌱</span> Section 1: Foundations
# <span class="emoji">🔁</span> Section 2: Collections and Loops
# <span class="emoji">🧰</span> Section 3: Functions and Data
# <span class="emoji">🚀</span> Section 4: Real-World Skills

</v-clicks>


---
layout: quote
---



# <span class="emoji">🌱</span> Section 1: Foundations

<v-clicks>

- **🔤 Chapter 1: Strings and Variables**
- **🔢 Chapter 2: Types, Numbers and Calculations**
- **🔀 Chapter 3: Making Decisions**
- **🧠 Chapter 4: Logic and Nesting**

</v-clicks>


---
layout: quote
---

# <span class="emoji">🔁</span> Section 2: Collections and Loops

<v-clicks>

- **📋 Chapter 5: Lists**
- **🔄 Chapter 6: For Loops**
- **⏳ Chapter 7: While Loops**


</v-clicks>


---
layout: quote
---

# <span class="emoji">🧰</span> Section 3: Functions and Data

<v-clicks>

- **⚙️ Chapter 8: Functions**
- **📖 Chapter 9: Dictionaries**
- **🎮 Projects**


</v-clicks>

---
layout: quote
---


# Projects <span class="emoji">🎮</span>
Some of the projects we will be making.

<v-clicks>

# <span class="emoji">✊✋✌️</span> Rock paper Scissors
# <span class="emoji">🔐</span> Random Password Generator
# <span class="emoji">🧮</span> Math Quiz Game
# <span class="emoji">❌⭕</span> Tic Tac Toe
# <span class="emoji">🔠</span> Hangman

</v-clicks>


---
layout: quote
---

# <span class="emoji">✊✋✌️</span> Rock Paper Scissors
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

# <span class="emoji">✊✋✌️</span> Rock Paper Scissors
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

# <span class="emoji">🔐</span> Random Password Generator

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

# <span class="emoji">🧮</span> Math Quiz Game
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

# <span class="emoji">❌⭕</span> Tic Tac Toe
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

# <span class="emoji">🔠</span> Hangman
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

# <span class="emoji">🚀</span> Section 4: Real-World Skills

<v-clicks>

- **📁 Chapter 10: Working with Files**
- **🛡️ Chapter 11: Exception Handling**
- **🏗️ Chapter 12: Object-Oriented Programming**


</v-clicks>


---
layout: quote
---

# Each chapter in more detail


---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 1: Strings and Variables <span class="emoji">🔤</span>

<v-clicks>


- Print text, add comments, and store data in variables
- Mix variables and text with f-strings
- Get user input with `input()`
- Transform text with `len()`, `.upper()`, `.lower()`, `.title()`, `.replace()`
- Pick out characters with `[]` and follow naming rules

</v-clicks>


---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 


# Chapter 2: Types, Numbers and Calculations <span class="emoji">🔢</span>

<v-clicks>


- Tell apart `str`, `int`, and `float`, and convert between them
- Do math with `+ - * / // % **` and use PEMDAS
- Fix errors from mixing text and numbers
- Format decimals (`:.2f`) and use `round()`, `min()`, `max()`
- Handle quotes and escape characters like `\n`

</v-clicks>


---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 3: Making Decisions <span class="emoji">🔀</span>

<v-clicks>

- Write `if` / `elif` / `else` statements
- Use `True` / `False` and comparison operators

</v-clicks>


---
layout: quote
---

#### 🌱 Section 1: Foundations

<br> 

# Chapter 4: Logic and Nesting <span class="emoji">🧠</span>

<v-clicks>

- Combine conditions with `and`, `or`, `not`
- Choose between multiple `if`s and `if/elif/else`
- Write nested `if` statements
- Clean up messy input with `.lower()` and `.strip()`
- Use truthy and falsy values

</v-clicks>



---
layout: quote
---

#### 🔁 Section 2: Collections and Loops

<br> 

# Chapter 5: Lists <span class="emoji">📋</span>

<v-clicks>

- Generate random numbers with `random`
- Create, access, change, add, and remove list items
- Slice, sort, reverse, search, and count
- Copy lists safely

</v-clicks>


---
layout: quote
---

#### 🔁 Section 2: Collections and Loops

<br> 

# Chapter 6: For Loops <span class="emoji">🔄</span>

<v-clicks>

- Loop through lists and strings, and repeat with `range()`
- Filter and process data by combining loops with `if`
- Build new lists, including list comprehensions
- Use `split` / `join`, tuples, and nested loops

</v-clicks>


---
layout: quote
---

#### 🔁 Section 2: Collections and Loops

<br> 

# Chapter 7: While Loops <span class="emoji">⏳</span>

<v-clicks>

- Repeat until a condition is met, using conditions, flags, `break`, and `continue`
- Validate user input
- Choose between `while` and `for`

</v-clicks>


---
layout: quote
---

#### 🧰 Section 3: Functions and Data

<br> 

# Chapter 8: Functions <span class="emoji">⚙️</span>

<v-clicks>


- Create functions with parameters, defaults, and `return`
- Use positional and keyword arguments
- Understand variable scope
- Import code with `import`, `as`, and `from ... import`

</v-clicks>


---
layout: quote
---

#### 🧰 Section 3: Functions and Data

<br> 

# Chapter 9: Dictionaries <span class="emoji">📖</span>

<v-clicks>

- Store, read, update, and delete key-value pairs
- Loop through dictionaries and use `.get()` for safe lookups
- Work with nested dictionaries and lists of dictionaries
- Write dictionary comprehensions and ternary expressions

</v-clicks>


---
layout: quote
---

#### 🧰 Section 3: Functions and Data

<br> 

# Projects <span class="emoji">🎮</span>
- Build full programs: Fruit Machine, Hangman, Cho-Han, Bagels, Tic-Tac-Toe, Coffee Machine, Blackjack

---
layout: quote
---

#### 🚀 Section 4: Real-World Skills

<br> 

# Chapter 10: Working with Files <span class="emoji">📁</span>

<v-clicks>

- Read, write, and append files
- Use `with` to close files safely
- Save and load structured data with JSON

</v-clicks>


---
layout: quote
---

#### 🚀 Section 4: Real-World Skills

<br> 

# Chapter 11: Exception Handling <span class="emoji">🛡️</span>

<v-clicks>

- Handle errors with `try` / `except` / `else` / `finally`
- Catch specific error types and print error messages
- Write retry loops for bad input

</v-clicks>


---
layout: quote
---

#### 🚀 Section 4: Real-World Skills

<br> 

# Chapter 12: Object-Oriented Programming <span class="emoji">🏗️</span>

<v-clicks>

- Create classes and objects
- Store data in attributes and set it up with `__init__()`
- Write methods with `self`
- Build programs with multiple objects

</v-clicks>



---
layout: quote
---

# Workspace setup


---
layout: center
---

# Step 1

<img src="./1.jpg" class="h-120 rounded shadow" />

---
layout: center
---

# Step 2

<img src="./2.jpg" class="h-120 rounded shadow" />

---
layout: center
---

# Step 3

<img src="./3.jpg" class="h-120 rounded shadow" />

---
layout: center
---

# Step 4

<img src="./4.jpg" class="h-120 rounded shadow" />

---
layout: center
---

# Step 5

<img src="./5.jpg" class="h-120 rounded shadow" />

---
layout: center
---

# Step 6

<img src="./6.jpg" class="h-120 rounded shadow" />

---
layout: center
---

# Done

<img src="./7.jpg" class="h-120 rounded shadow" />