# 🐍 Python & Pandas for Data Analysis

## 🚀 Overview

This project showcases the Python and Pandas skills developed during my **Data Technician Bootcamp** through a combination of programming exercises, data analysis tasks, and practical notebook projects. Working with real-world datasets, I used Python to build logical programs, automate calculations, manipulate data, and generate insights through analysis and visualisation. 

The project focused on developing core programming skills alongside data analysis techniques using **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**, enabling me to clean, transform, explore, analyse, and visualise data effectively.

---

## 🛠️ Skills & Techniques Applied

### 🐍 Python Fundamentals

✅ Variables & Data Types  
✅ `print()` Function  
✅ `input()` Function  
✅ Type Casting (`int()`, `float()`, `str()`)  
✅ Conditional Statements (`if`, `elif`, `else`)  
✅ `for` Loops  
✅ `while` Loops  
✅ Functions  
✅ Lists & Dictionaries  
✅ String Manipulation

### 💡 Programming Logic

✅ User Input Validation  
✅ Decision-Making Logic  
✅ Iteration & Repetition  
✅ Calculations & Formula-Based Solutions  
✅ Error Handling Concepts  
✅ Problem Solving & Algorithmic Thinking

### 🐼 Pandas Data Analysis

✅ DataFrames & Series  
✅ Data Import & Export  
✅ Data Filtering  
✅ Data Selection with `.loc[]`  
✅ Data Selection with `.iloc[]`  
✅ Column Selection & Creation  
✅ Data Inspection & Exploration  
✅ Data Cleaning  
✅ Data Transformation  
✅ Data Aggregation  
✅ Data Merging & Joining

### ⚙️ Pandas Methods & Functions

✅ `head()`  
✅ `tail()`  
✅ `info()`  
✅ `describe()`  
✅ `dtypes`  
✅ `columns`  
✅ `shape`  
✅ `value_counts()`  
✅ `unique()`   
✅ `isnull()`  
✅ `dropna()`  
✅ `fillna()`  
✅ `groupby()`  
✅ `sort_values()`  
✅ `merge()`  
✅ `concat()`  
✅ `reset_index()`  
✅ `rename()`  
✅ `drop()`  
✅ `loc[]`  
✅ `iloc[]`

### 📊 Data Visualisation

✅ Matplotlib  
✅ Seaborn  
✅ Line Charts  
✅ Bar Charts  
✅ Histograms  
✅ Scatter Plots  
✅ Box Plots  
✅ Count Plots  
✅ Distribution Analysis  
✅ Exploratory Data Visualisation

---

## 💡 Project Highlights

### 🐍 Python Programming

- Built programs using variables, user input, and conditional logic
- Applied loops to automate repetitive tasks and calculations
- Created solutions for real-world programming challenges
- Developed interactive programs that respond dynamically to user input
- Strengthened problem-solving and logical thinking skills through practical exercises including FizzBuzz and other coding challenges

### 🧮 Calculations & User Interaction

- Performed mathematical and business-related calculations
- Created programs that validate and process user input
- Used decision-making structures to control program flow
- Developed applications that generate outputs based on user choices and conditions

### 🐼 Data Analysis with Pandas

- Loaded and explored structured datasets using DataFrames
- Examined dataset structure using `info()`, `dtypes`, `columns`, and `shape`
- Investigated data using `head()`, `tail()`, and `describe()`
- Filtered and sliced data using `.loc[]` and `.iloc[]`
- Applied sorting, grouping, and aggregation techniques using `sort_values()` and `groupby()`
- Analysed categorical information using `value_counts()` and `unique()`
- Combined datasets using `merge()` and `concat()`
- Explored retail, sales, and business datasets to uncover trends and patterns

### 🧹 Data Cleaning & Preparation

- Identified missing values using `isnull()`
- Handled incomplete data using `dropna()` and `fillna()`
- Renamed, removed, and transformed columns where required
- Improved dataset quality and consistency for analysis
- Prepared datasets for reporting, visualisation, and business insights

### 📈 Data Visualisation

- Created visualisations using Matplotlib and Seaborn
- Produced bar charts, line charts, scatter plots, histograms, and box plots
- Explored distributions, trends, and relationships within datasets
- Identified patterns, outliers, and key business insights through visual analysis
- Supported data storytelling through clear and effective visualisations

---

## 🎯 Key Deliverables

✅ Python Programming Exercises  
✅ Logic-Based Problem Solving  
✅ Interactive Python Applications  
✅ Pandas Data Analysis Notebooks  
✅ Data Cleaning & Transformation  
✅ Data Visualisations & Reporting  
✅ Business Insight Generation

---

## 📖 Data Analysis & Storytelling

A key focus of this project was transforming raw data into meaningful insights through Python and Pandas. By combining programming logic, data manipulation, and data visualisation techniques, I developed the ability to explore datasets, identify trends, and communicate findings through clear and impactful analysis.

---

## 🔧 Tools & Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebooks
- CSV Datasets

---

## 🏆 Skills Showcase

`Python` • `Pandas` • `Data Analysis` • `Data Cleaning` • `Data Manipulation` • `DataFrames` • `.loc[]` • `.iloc[]` • `groupby()` • `sort_values()` • `dropna()` • `fillna()` • `Matplotlib` • `Data Visualisation` • `Problem Solving`

---

⭐ This project demonstrates my ability to use Python and Pandas to build logical solutions, clean and analyse data, create visualisations, and transform raw datasets into actionable insights.



## Data Visualisation 

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/35a54368-a269-4672-8092-f41c37bfe9fa" />  
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/021cd587-e8b5-4fa5-9e57-983f76328684" />

## Data Analysis

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/8d4bbd64-b9cc-4d5d-a8f5-f1de0eaa9587" />

## Python Programming
-  You're developing a simple calculator tool for a local community learning website. Users should be able to choose what operation they want to perform and continue using the calculator until they decide to exit.
🧪 Task: Write a Python program that: Displays a menu with the following options: 1- Addition 2- Subtraction 3- Multiplication 4-Division 5- Exit. Asks the user to choose an operation. Asks for two numbers, then performs the chosen operation. Repeats the menu until the user selects Exit
'''
option = 0

while option != 5:
  print("1- Addition")
  print("2- Subtraction")
  print("3- Multiplication")
  print("4- Division")
  print("5- Exit")

  option = int(input("Enter option:"))

  if option < 5:
    num1 = int(input("Enter first number: "))
    num2 = int(input("Enter second number: "))
  if option == 1:
    print(f"{num1} + {num2} =",num1 + num2)
  elif option == 2:
    print(f"{num1} - {num2} =",num1 - num2)
  elif option == 3:
    print(f"{num1} * {num2} =",num1 * num2)
  elif option == 4:
    if num2 == 0:
      print("Cannot divide by zero")
    else:
      print(f"{num1} / {num2} =",num1 / num2)
  elif option == 5:
    print("Exit")
  else:
    print("Invalid option")
'''

- You’re building a tool for a puzzle game where certain levels require calculating the factorial of a number to unlock a clue. A factorial of a number is the product of all positive integers from 1 up to that number. For example: 5! = 5 × 4 × 3 × 2 × 1 = 120
🧪 Task: Write a Python program that: Asks the user to enter a non-negative integer. Calculates the factorial of that number. Displays the result
'''
number = int(input("Please enter a number:"))
total = 1
for i in range(1, number+1):
  total = total *i
print(f"Total of all numbers from 1 to {number} is {total}.")
'''
