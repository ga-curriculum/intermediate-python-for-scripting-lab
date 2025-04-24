<h1>
  <span class="headline">Intermediate Python for Scripting Lab</span>
  <span class="subhead">Functions and Modular Code</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create functions in Python.

## Setup

Create a new file named <code class="filepath">functions.py</code> in your <code class="filepath">intermediate-python-for-scripting-lab</code> directory. This file will contain all the code for this exercise.

## Exercises

1. Create a function `validate_age(age)` that:

   - Takes an age as input.
   - Raises a `ValueError` if the age is not a positive integer. Otherwise, it should return the age.
   - Includes a docstring explaining the function's behavior and how to handle the potential `ValueError`.

2. Create two functions:

   - `calculate_rectangle_area(length, width)`
     - This function should take the length and width of a rectangle as arguments and return the area of the rectangle.
   - `calculate_circle_area(radius)`
     - This function should take the radius of a circle as an argument and return the area of the circle.
   - Then, create a third function `get_area(shape, *args)`.
     - This function should take the shape (`"rectangle"` or `"circle"`) and the necessary dimensions as arguments.
     - This function should call the appropriate area calculation function (either `calculate_rectangle_area()` or `calculate_circle_area()` - passing the appropriate arguments to each).
