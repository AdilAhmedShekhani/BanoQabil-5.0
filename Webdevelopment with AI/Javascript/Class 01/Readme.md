# JavaScript Basics for Students 🚀

## Introduction
In this class, we learned the basic concepts of JavaScript. These topics help students understand how JavaScript works inside the browser.

---

# 1. Alert
`alert()` is used to show a popup message on the screen.

## Example
```javascript
alert("Welcome to JavaScript Class!")
```

## Output
A popup box will appear with the message.

---

# 2. Prompt
`prompt()` is used to take input from the user.

## Example
```javascript
let userName = prompt("Enter your name")
console.log(userName)
```

## What Happens?
- User types the name.
- The value is stored in a variable.
- It is shown in the console.

---

# 3. Console.log
`console.log()` is used to print data in the browser console.

## Example
```javascript
console.log("Hello Students")
```

## Why We Use It?
- To check output
- To debug code
- To test variables

---

# 4. Variables
Variables are used to store data.

## Example
```javascript
let city = "Karachi"
console.log(city)
```

---

# 5. Legal and Illegal Variable Names

## ✅ Legal Variable Names
```javascript
let userName
let age1
let first_name
let $price
```

## ❌ Illegal Variable Names
```javascript
let 1name
let user-name
let var
let first name
```

## Important Rules
- Variable name cannot start with a number.
- Spaces are not allowed.
- Special symbols are not allowed except `_` and `$`.
- Reserved keywords cannot be used.

---

# 6. Camel Case
In camelCase, the first word starts with a small letter and the next word starts with a capital letter.

## Example
```javascript
let firstName
let studentAge
```

---

# 7. Snake Case
In snake_case, words are connected with underscores `_`.

## Example
```javascript
let first_name
let student_age
```

---

# 8. Normal Case
Normal case means simple naming style.

## Example
```javascript
let name
let city
```

---

# 9. Variable Declare and Call

## Step 1: Declare Variable
```javascript
let studentName
```

## Step 2: Assign Value
```javascript
studentName = "Ali"
```

## Step 3: Call Variable
```javascript
console.log(studentName)
```

---

# 10. Data Types
JavaScript has different data types.

## String
```javascript
let name = "Ahmed"
```

## Number
```javascript
let age = 20
```

## Boolean
```javascript
let isStudent = true
```

---

# 11. Concatenation
Concatenation means joining strings together.

## Example
```javascript
let firstName = "Ali"
let lastName = "Khan"

console.log(firstName + " " + lastName)
```

## Output
```javascript
Ali Khan
```

---

# 12. Assignment: Make a Table Using Prompt

## Task
Take user input using `prompt()` and display student information in table form.

## Example Code
```javascript
let studentName = prompt("Enter Student Name")
let studentAge = prompt("Enter Student Age")
let studentCity = prompt("Enter Student City")

console.log("Name: " + studentName)
console.log("Age: " + studentAge)
console.log("City: " + studentCity)
```

---

# Practice Task 💻
Create your own student information program using:
- alert
- prompt
- console.log
- variables
- concatenation

---

# Final Note ✨
Practice daily and try different examples yourself. JavaScript becomes easy when you write code regularly.

