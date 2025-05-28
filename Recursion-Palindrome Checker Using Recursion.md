#  Recursion:Palindrome Checker Using Recursion in Python

##  AIM:
To write a Python program to check whether a given string is a **palindrome** using **recursion**.

---

##  ALGORITHM:

1. **Start**
2. Define a recursive function `is_palindrome(word)`
   - **Base Case:** If the string length is less than 1, return `True`
   - **Recursive Case:** If the first and last characters match, call the function recursively on the substring without first and last characters
   - Else, return `False`
3. Get input from the user
4. Call the recursive function
5. Print whether the string is a palindrome
6. **Stop**

---

##  PROGRAM:
```python

def is_palindrome(word):
    return len(word) < 1 or (word[0] == word[-1] and is_palindrome(word[1:-1]))

print("Palindrome" if is_palindrome(input("Enter a word: ")) else "Not a palindrome")

```

## OUTPUT
![image](https://github.com/user-attachments/assets/66b3a619-6ee5-4665-860d-632ae21d6257)

## RESULT
Thus, the program has been successfully executed.
