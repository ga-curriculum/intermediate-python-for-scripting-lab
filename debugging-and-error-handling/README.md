<h1>
  <span class="headline">Intermediate Python for Scripting Lab</span>
  <span class="subhead">Debugging and Error Handling</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to use try-except blocks and raise custom errors.

## Setup

Create a new file named <code class="filepath">debugging.py</code> in your <code class="filepath">intermediate-python-for-scripting-lab</code> directory. This file will contain all the code for this exercise.

## Exercises

1. Below is some code that attempts to divide two numbers. However, it can encounter a `ZeroDivisionError` error. Use a `try`/`except` block to handle this error and print an informative message.

   ```python
   def divide_numbers(num1, num2):
       return num1 / num2
   ```

2. Create a function with a logical name of your choice. It should:
   - Validate an email address using this criteria:
     - If the email address does not contain an `@` symbol, it is not valid.
   - Raise a custom exception called `InvalidEmailError` when there is an invalid email.
