<h1>
  <span class="headline">Intermediate Python for Scripting Lab</span>
  <span class="subhead">Functions and Code Organization</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create functions in Python.

# Exercises

1. Create a function `validate_age(age)` that takes an age as input. The function should raise a `ValueError` if the age is not a positive integer.  Otherwise, it should return the age.  Include a docstring explaining the function's behavior and how to handle the potential `ValueError`.

2. Create two functions: `calculate_rectangle_area(length, width)` and `calculate_circle_area(radius)`.  Each function should return the calculated area.  Then, create a third function `get_area(shape, *args)` that takes the shape ("rectangle" or "circle") and the necessary dimensions as arguments. This function should call the appropriate area calculation function.
