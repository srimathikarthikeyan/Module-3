# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Define a function match(txt) that takes a string txt as input.
3. Inside the function, define a regular expression pattern ^a(b*)$ to match strings starting with 'a' and followed by zero or more 'b's.
4. Use re.search() to search for the pattern in the input string txt.
5. If the pattern matches, return the string 'Not matched!'.
6. If the pattern does not match, return the string 'Found a match!'.
7. Input a string from the user and store it in a variable str.
8. Call the match(str) function and print the result.  
9. Terminate the program.

---

### PROGRAM

    import re
    def match(txt):
        pattern = '^a(b*)$'
        if re.search(pattern, txt):
            return 'Not matched!'
        else:
            return 'Found a match!'
    str = input()
    print(match(str))

### OUTPUT

![image](https://github.com/user-attachments/assets/7524a2a7-3425-49ee-ae07-3380bc09f8f2)


### RESULT
Thus, the python program that matches the pattern has been implemented and executed successfully.
