# Experiment---7
- Aim : Study of Loops in Python

  **Theory:**
These programs are based on the while loop, which repeatedly executes a block of code as long as the given condition is True. A loop variable is initialized before the loop and updated inside it to avoid infinite execution.

- The codes demonstrate different applications of the while loop such as:
- Generating number sequences (printing 1 to N).
- Mathematical calculations like factorial and Fibonacci series using repeated multiplication or addition.
- Digit manipulation (reversing a number, counting digits) using modulus (%) and floor division (//).
- Palindrome checking by comparing original and reversed values (for numbers and strings).
- Searching elements in a list using linear search technique.
- Using control statements like break (to exit loop early) and continue (to skip an iteration).
Overall, these programs show how while loops are used for repetition, decision-making, arithmetic operations, and data processing in Python.

**🔹 Algorithms :**

1️⃣ Print Numbers from 1 to N
Algorithm:
- Start
- Input value of N
- Set i = 1
- While i ≤ N
- Print i
- Increment i by 1
- Stop

2️⃣ Factorial of a Number
Algorithm:
- Start
- Input number n
- Set fact = 1
- While n > 0
- Multiply fact = fact × n
- Decrease n by 1
- Print fact
- Stop

3️⃣ Fibonacci Series (n terms)
Algorithm:
- Start
- Input number of terms n
- Set a = 0, b = 1, i = 1
- While i ≤ n
- Print a
- Set c = a + b
- Set a = b
- Set b = c
- Increment i by 1
- Stop

4️⃣ Reverse of a Number
Algorithm:
- Start
- Input number n
- Set rev = 0
- While n > 0
- Get last digit digit = n % 10
- Update rev = rev × 10 + digit
- Remove last digit n = n // 10
- Print rev
- Stop

5️⃣ Check Palindrome (Number)
Algorithm:
- Start
- Input number num
- Store temp = num
- Set rev = 0
- While num > 0
- Update rev = rev × 10 + (num % 10)
- Set num = num // 10
- If temp == rev
- Print "Palindrome"
- Else print "Not Palindrome"
- Stop

6️⃣ Count Digits in a Number
Algorithm:
- Start
- Input number num
- Set count = 0
- While num > 0
- Increment count by 1
- Set num = num // 10
- Print count
- Stop

7️⃣ Search Element in a List (Linear Search)
Algorithm:
- Start
- Define list nums
- Input key to search
- Set i = 0
- While i < length of list
- If nums[i] == key
- Print index
- Stop
- Increment i
- If not found, print "Element not found"
- Stop

  **Conclusion:**
The while loop is used to repeatedly execute a block of code as long as a condition is true. It helps perform calculations, number operations, searching, and logical checks efficiently. Overall, it is an important control structure for handling repetition in Python programs.



