
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
