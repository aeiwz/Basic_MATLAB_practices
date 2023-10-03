# Basic MATLAB practices

---

## Basic command
1. **Basic Arithmetic:**
   - Addition: `a + b`
   - Subtraction: `a - b`
   - Multiplication: `a * b`
   - Division: `a / b`

2. **Variables:**
   - Assigning a value to a variable: `variable_name = value`

3. **Displaying Output:**
   - Use `disp` to display text or the value of a variable.
     ```matlab
     disp('Hello, MATLAB!')
     disp(variable_name)
     ```

4. **Vectors and Matrices:**
   - Creating a row vector: `v = [1, 2, 3]`
   - Creating a column vector: `v = [1; 2; 3]`
   - Creating a matrix: `A = [1, 2; 3, 4]`

5. **Matrix Operations:**
   - Matrix multiplication: `A * B`
   - Element-wise operations:
     - Addition: `A + B`
     - Subtraction: `A - B`
     - Element-wise multiplication: `A .* B`
     - Element-wise division: `A ./ B`

6. **Functions:**
   - Define a function in a separate `.m` file, or use anonymous functions.
     ```matlab
     % Anonymous function
     f = @(x) x^2;
     ```

7. **Plotting:**
   - Create 2D plots using `plot` or `scatter`.
     ```matlab
     x = linspace(0, 2*pi, 100);
     y = sin(x);
     plot(x, y)
     ```

8. **Control Flow:**
   - Use `if`, `else`, and `elseif` for conditional statements.
   - Use `for` and `while` loops for iteration.
   
9. **Data Import/Export:**
   - Load data from a file: `data = load('filename.txt')`
   - Save data to a file: `save('output.mat', 'variable_name')`

10. **Comments:**
    - Add comments using `%` to make your code more understandable.

11. **Help and Documentation:**
    - Use `help` or `doc` followed by a function or topic name to get documentation.

12. **Clearing Variables:**
    - Clear variables from the workspace: `clear variable_name`

13. **Exiting MATLAB:**
    - To exit MATLAB, type `exit` or close the MATLAB window.

14. **Getting Started:**
    - MATLAB has a GUI, but you can also use the command-line interface. Start by typing `matlab` in your terminal.

15. **Online Resources:**
    - MATLAB has extensive documentation and a large user community. You can find tutorials and help online.

---

## Basic syntax

1. **Comments:**
   - Comments are preceded by `%` and are used for adding explanations to your code.
   ```matlab
   % This is a comment
   ```

2. **Variables:**
   - Variables are created by assigning values to them.
   ```matlab
   variable_name = value;
   ```

3. **Displaying Output:**
   - Use `disp` to display text or variable values.
   ```matlab
   disp('Hello, MATLAB!');
   ```

4. **Arithmetic Operators:**
   - MATLAB supports basic arithmetic operations: `+`, `-`, `*`, `/`.
   ```matlab
   result = a + b;
   ```

5. **Vectors and Matrices:**
   - Define vectors and matrices using square brackets `[ ]`.
   ```matlab
   vector = [1, 2, 3];
   matrix = [1, 2; 3, 4];
   ```

6. **Functions:**
   - MATLAB functions are called with parentheses.
   ```matlab
   result = some_function(argument1, argument2);
   ```

7. **Conditional Statements:**
   - Use `if`, `else`, and `elseif` for conditional execution.
   ```matlab
   if condition
       % code to execute when the condition is true
   else
       % code to execute when the condition is false
   end
   ```

8. **Loops:**
   - Use `for` and `while` loops for iteration.
   ```matlab
   for i = 1:5
       % code to repeat 5 times
   end

   while condition
       % code while the condition is true
   end
   ```

9. **Functions and Script Files:**
   - Functions are stored in `.m` files, while scripts are sequences of MATLAB commands.
   ```matlab
   % Function in a separate file (my_function.m)
   function result = my_function(arg1, arg2)
       % function code here
   end

   % Script file
   variable = my_function(input1, input2);
   ```

10. **Data Import/Export:**
    - Load data from a file using `load`, and save data using `save`.
    ```matlab
    data = load('datafile.mat');
    save('output.mat', 'variable_name');
    ```
