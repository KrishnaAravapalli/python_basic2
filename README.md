# Python Mathematical Operations

This project contains two Python programs:
1. **Factorial Calculation** - Uses recursion to calculate the factorial of a given number.
2. **Math Module Calculations** - Uses the `math` module to compute the square root, natural logarithm, and sine of a number.

## Task 1: Factorial Calculation Using a Function
### **Problem Statement**
- Defines a function `factorial(n)` that calculates the factorial of a given number using recursion.
- Takes user input and calls the function.
- Displays the factorial of the input number.

### **Code Explanation**
- If the input number is `0` or `1`, the function returns `1`.
- Otherwise, it recursively multiplies `n` by `factorial(n-1)`.
- Handles negative numbers by displaying an appropriate message.

### **Example Output**
```
Enter a number: 5
The factorial of 5 is: 120
```

---

## Task 2: Using the Math Module for Calculations
### **Problem Statement**
- Asks the user for a number.
- Uses Python’s `math` module to compute:
  - **Square root** of the number
  - **Natural logarithm (log base e)** of the number
  - **Sine (in radians)** of the number
- Displays the results.

### **Code Explanation**
- Uses `math.sqrt()` for square root.
- Uses `math.log()` for natural logarithm.
- Uses `math.sin()` to compute the sine of the number in radians.

### **Example Output**
```
Enter a number: 25

Results for the number 25.0:
Square root: 5.0
Logarithm (log base e): 3.2188758248682006
Sine: -0.13235175009777303
```

---

## How to Run the Program
1. Ensure you have Python installed (Python 3+ recommended).
2. Copy the script to a file (e.g., `script.py`).
3. Open a terminal or command prompt and navigate to the script’s directory.
4. Run the script using:
   ```sh
   python script.py
   ```

## Author
**Krishna Aravapalli**

Feel free to contribute, suggest improvements, or report issues!
