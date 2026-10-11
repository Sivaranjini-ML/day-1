
learning& growing
# day-1
name = input("Enter your name: ")        print("Hello", name)                                                                  names = ["Anu", "Ravi", "Priya", "Karthik", "Meena"]    print(names)
# Day 2 - Python Strings
# 60-Day Career Journey

# 1. Store a name
name = "Sivaranjini"

# 2. Print the first character
print("First character:", name[0])

# 3. Print the last character
print("Last character:", name[-1])

# 4. Find the length
print("Length:", len(name))

# 5. Convert to uppercase
print("Uppercase:", name.upper())

# 6. Convert to lowercase
print("Lowercase:", name.lower())

# 7. Reverse the string
print("Reverse:", name[::-1])


#day 4
# DSA - String Practice

word = "Python"

# First character
print("First character of Python:", word[0])

# Last character
print("Last character of Python:", word[-1])

# Length
print("Length of Python:", len(word))

# Reverse
print("Reverse of Python:", word[::-1])

# Day 3 - Python Dictionaries
# 60-Day Career Journey

# Student information
student = {
    "name": "Siva",
    "age": 20,
    "dept": "CSE",
    "college": "ABC",
    "city": "Chennai"
}

print("Name:", student["name"])
print("Age:", student["age"])
print("Department:", student["dept"])
print("College:", student["college"])
print("City:", student["city"])


# Student marks
marks = {
    "Siva": 85,
    "Velu": 95,
    "Jan": 90,
    "Kavi": 92
}

# Print one student's mark
print("Velu's mark:", marks["Velu"])

# Add a new student
marks["Arun"] = 90

# Find highest mark
print("Highest mark:", max(marks.values()))

# Print all students and marks
for name, mark in marks.items():
    print(name, ":", mark)

# Day4_Python_Functions.py
# Day 4: Python Functions and DSA Practice

# Q1: Greeting function
def greet():
    print("Good Morning")

greet()


# Q2: Add two numbers
def add(a, b):
    return a + b

print("Sum:", add(15, 25))


# Q3: Check even or odd
def check_even(num):
    if num % 2 == 0:
        print("Even")
    else:
        print("Odd")

check_even(8)


# Q4: Find the largest number
def find_largest(a, b, c):
    return max(a, b, c)

print("Largest:", find_largest(10, 50, 70))


# Q5: Find the square
def square(num):
    return num * num

print("Square:", square(7))


# DSA Q1: Sum of a list
numbers = [10, 20, 30, 40, 50]
print("Sum of list:", sum(numbers))


# DSA Q2: Count list items
numbers = [5, 10, 15, 20, 25]
print("Number of items:", len(numbers))


# DSA Q3: Find the largest item in a list
numbers = [12, 45, 23, 67, 34]
print("Largest item:", max(numbers)

# Day5_SQL_Practice.sql
-- Day 5: SQL Practice
-- Topic: SELECT, WHERE, ORDER BY, ASC, DESC

-- Q1: Display all student records
SELECT * FROM students;

-- Q2: Display only student names
SELECT name FROM students;

-- Q3: Find students who scored more than 80
SELECT * FROM students
WHERE marks > 80;

-- Q4: Find students in the CSE department
SELECT * FROM students
WHERE department = 'CSE';

-- Q5: Display students in descending order of marks
SELECT * FROM students
ORDER BY marks DESC;

-- Q6: Display names of students who scored more than 80
SELECT name FROM students
WHERE marks > 80;

-- Q7: Display all students from lowest to highest marks
SELECT * FROM students
ORDER BY marks ASC;
