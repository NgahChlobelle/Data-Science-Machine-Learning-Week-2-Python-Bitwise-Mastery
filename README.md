# PYTHON OPERATORS AND BITWISE LOGIC FOUNDATIONS

# OBJECTIVES
## To master the fundamental Python operators including arithmetic, cmparison, logical, assignment and bitwise operators
## To understand the manual mathematical processes (decimal and binary paths) behind bitwise shifting and base conversions.

# TOOLS USED
## Programming Language: Python
## Environment: Jupyter Notebook

# STEP-BY-STEP PROCESS
## 1. Arithmetic & Comparison Testing
### Executed basic mathematical operations and tested true values using comparison operators to verify how Python handles different data types (integers vs. floats)
## 2. Assignment Shorthand
### Practices 'In-place' updates to variables using assignment operators to simplify code structure
## 3. Bitwise Analysis
### Conversion:
#### - Performed conversion of decimal numbers (10 and 3) into binary using the successive division by 2 method.
### Logic Mapping:
#### - Mapped the results of AND, OR, and XOR operations by comparing butsat each position.
### Shifting:
#### - Verified the 'Decimal Path' (multiplication/division by 2) against a 'Binary path' (moving bits left or right).

# COMMANDS EXECUTED
## 1. ARITHMETIC IN PYTHON (+, -, *, /, //, %, **)
### Addition : (x + y) 
### Subtraction : (x - y)
### Multiplication : print( x * y)
### Division : (x / y)
### Floor Division : (x // y)
### Modulus : (x % y)
### Exponential : (x ** y)
## 2. COMPARISON OPERATORS : (>, <, =, >=, <=, !=)
### Greater than : (x > y)
### Less than : (x < y)
### Equal to : (x == y)
### Greater than or Equal to : (x >= y)
### Less than or Equal to : (x <= y)
### Not Equal to : (x != y)
## 3. LOGICAL OPERATORS (and, or & not)
### AND : (x > 30 and y < 25)
### OR : (x > 30 or y < 25)
### NOT : not(x < 32)
## 4. ASSIGNMENT OPERATORS (=)
### Addition Assignment : x += 23
### Subtraction Assignment : x -= 8
### Multiplication Assignment : x *= 2
### Division Assignment : x /= 10
### Modulus Assignment : x %= 10
### Floor Division Assignment : x //= 10
### Exponent Assignment : x **= 2
## BITWISE OPERATIONS (&, |, ^, ~, <<, >>)
### AND Operator : (x & y)
### OR Operator : (x | y)
### Exclusive OR (XOR) Operator : (x ^ y)
### Bitwise Negation : (~x); (Formula = -(x+1))
### Right Shift : (x >> 2)
### Left Shift : (x << 3)
### bin : bin(10)

# SCREENSHOTS OF RESULTS
![image alt](https://github.com/NgahChlobelle/Data-Science-Machine-Learning-Week-2-Python-Bitwise-Mastery/blob/5c03fc75ae5f7fe0f8d559341c2802809b54da38/Python%20Operators%20and%20Bitwise%20Logic%20Foundation%201.PNG)

# KEY OBSERVATION / LESSONS LEARNED
## - Floor Division vs. Right Shift: A right shift x >> n is functionally identical to floor division x // (2**n).
## - Left Shift Efficiency: Shifting left x << n is a faster way to perform multiplication by powers of 2.
## - Bitwise Negation Formula: The ~x operator follows the formula -(x+1). For Example, ~10 results in ~11.
## - Binary Representation: Python uses 0b to denote binary strings (e.g., bin(10) returns '0b1010').
## - Data Integrity: Manual verification (Successive Division) is essential for debugginh complex bitwiselogic in data science and machine learning applications.
