---
title: Exercise for module 1
description: "Exercises to practice Rust"
duration: 90 minutes
---

Topic: Functions

Program requirements:

- Displays your first and last name

Notes:

- Use a function to display your first name
- Use a function to display your last name
- Use the println macro to display messages to the terminal

---

Topic: Basic arithmetic

Program requirements:

- Displays the result of the sum of two numbers

Notes:

- Use a function to add two numbers together
- Use a function to display the result
- Use the "{:?}" token in the println macro to display the result

---

Topic: Flow control using if..else

Program requirements:

- Displays a message based on the value of a boolean variable
- When the variable is set to true, display "hello"
- When the variable is set to false, display "goodbye"

Notes:

- Use a variable set to either true or false
- Use an if..else block to determine which message to display
- Use the println macro to display messages to the terminal

---

Topic: Flow control using if..else if..else

Program requirements:

- Display ">5", "<5", or "=5" based on the value of a variable
  is > 5, < 5, or == 5, respectively
  Notes:
- Use a variable set to any integer value
- Use an if..else if..else block to determine which message to display
- Use the println macro to display messages to the terminal

---

Topic: Decision making with match

Program requirements:

- Display "it's true" or "it's false" based on the value of a variable
  Notes:
- Use a variable set to either true or false
- Use a match expression to determine which message to display

---

Topic: Decision making with match

Program requirements:

- Display "one", "two", "three", or "other" based on whether the value of a variable is 1, 2, 3, or some other number, respectively
  Notes:
- Use a variable set to any integer
- Use a match expression to determine which message to display
- Use an underscore (\_) to match on any val

---

Topic: Looping using the loop statement

Program requirements:

- Display "1" through "4" in the terminal
  Notes:
- Use a mutable integer variable
- Use a loop statement
- Print the variable within the loop statement
- Use break to exit the loop

---

Topic: Looping using the while statement

Program requirements:

- Counts down from 5 to 1, displays the countdown in the terminal, then prints "done!" when complete.

Notes:

- Use a mutable integer variable
- Use a while statement
- Print the variable within the while loop
- Do not use break to exit the loop

---

Topic: Working with an enum

Program requirements:

- Prints the name of a color to the terminal

Notes:

- Use an enum with color names as variants
- Use a function to print the color name
- The function must use the enum as a parameter
- Use a match expression to determine which color
  name to print

---

Topic: Organizing similar data using structs

Requirements:

- Print the flavor of a drink and it's fluid ounces

Notes:

- Use an enum to create different flavors of drinks
- Use a struct to store drink flavor and fluid ounce information
- Use a function to print out the drink flavor and ounces
- Use a match expression to print the drink flavor

---

Topic: Data management using tuples

Requirements:

- Print whether the y-value of a cartesian coordinate is
  greater than 5, less than 5, or equal to 5

Notes:

- Use a function that returns a tuple
- Destructure the return value into two variables
- Use an if..else if..else block to determine what to print

---

Topic: Working with expressions

Requirements:

- Print "its big" if a variable is > 100
- Print "its small" if a variable is <= 100

Notes:

- Use a boolean variable set to the result of
  an if..else expression to store whether the value
  is > 100 or <= 100
- Use a function to print the messages
- Use a match expression to determine which message
  to print

---

Topic: Ownership

Requirements:

- Print out the quantity and id number of a grocery item

Notes:

- Use a struct for the grocery item
- Use two i32 fields for the quantity and id number
- Create a function to display the quantity, with the struct as a parameter
- Create a function to display the id number, with the struct as a parameter

---

Topic: Implementing functionality with the impl keyword

Requirements:

- Print the characteristics of a shipping box
- Must include dimensions, weight, and color

Notes:

- Use a struct to encapsulate the box characteristics
- Use an enum for the box color
- Implement functionality on the box struct to create a new box
- Implement functionality on the box struct to print the characteristics

---

Topic: Vectors

Requirements:

- Print 10, 20, "thirty", and 40 in a loop
- Print the total number of elements in a vector

Notes:

- Use a vector to store 4 numbers
- Iterate through the vector using a for..in loop
- Determine whether to print the number or print "thirty" inside the loop
- Use the .len() function to print the number of elements in a vector

---

Topic: Strings

Requirements:

- Print out the name and favorite colors of people aged 10 and under

Notes:

- Use a struct for a persons age, name, and favorite color
- The color and name should be stored as a String
- Create and store at least 3 people in a vector
- Iterate through the vector using a for..in loop
- Use an if expression to determine which person's info should be printed
- The name and colors should be printed using a function

---

Topic: Advanced match

Requirements:

- Print out a list of tickets and their information for an event
- Tickets can be Backstage, Vip, and Standard
- Backstage and Vip tickets include the ticket holder's name
- All tickets include the price

Notes:

- Use an enum for the tickets with data associated with each variant
- Create one of each ticket and place into a vector
- Use a match expression while iterating the vector to print the ticket info

---

Topic: Option

Requirements:

- Print out the details of a student's locker assignment
- Lockers use numbers and are optional for students

Notes:

- Use a struct containing the student's name and locker assignment
- The locker assignment should use an Option<i3
- Use a struct containing the student's name and locker assignment
- The locker assignment should use an Option<i32>

---

Topic: Browsing standard library documentation

Requirements:

- Print a string in lowercase and uppercase

Notes:

- Utilize standard library functionality to
  transform the string to lowercase and uppercase
- Use 'rustup doc' in a terminal to open the standard library docs
- Navigate to the API documentation section
- Search for functionality to transform a string (or str)
  to uppercase and lowercase
  - Try searching for: to_uppercase, to_lowercase

---

Topic: Result

Requirements:

- Create an structure named `Adult` that represents a person aged 21 or older:
  - The structure must contain the person's name and age
  - Implement Debug print functionality using `derive`
- Implement a `new` function for the `Adult` structure that returns a Result:
  - The Ok variant should contain the initialized structure, but only
    if the person is aged 21 or older
  - The Err variant should contain a String (or &str) that explains why
    the structure could not be created
- Instantiate two `Adult` structures:
  - One should be aged under 21
  - One should be 21 or over
- Use `match` to print out a message for each `Adult`:
  - For the Ok variant, print any message you want
  - For the Err variant, print out the error message

---

Topic: HashMap

Requirements:

- Print the name and number of items in stock for a furniture store
- If the number of items is 0, print "out of stock" instead of 0
- The store has:
  - 5 Chairs
  - 3 Beds
  - 2 Tables
  - 0 Couches
- Print the total number of items in stock

Notes:

- Use a HashMap for the furniture store stock
