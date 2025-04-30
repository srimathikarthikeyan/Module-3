# Exp.No:3e
## SEB - FIND SEQUENCE USING REGEX

---

### AIM  
To Write a Python program to find sequences of Lower case letters joined with a '@'.

---

### ALGORITHM

1. Begin the program.  
2. Define a function match(txt) that takes a string txt as input.
3. Inside the function, define a regular expression pattern [a-z]@[a-z] to match any string that contains a lowercase letter, followed by the '@' symbol, and then another lowercase letter.
4. Use re.search() to search for the pattern in the input string txt.
5. If the pattern is found in the string, return the string 'Found a match!'.
6. If the pattern is not found, return the string 'Not matched!'.
7. Input a string from the user and store it in the variable string.
8. Call the match(string) function and print the result.
9. Terminate the program.

---

### PROGRAM

    import re
    def match(txt):
        pattern = '[a-z]@[a-z]'
        if re.search(pattern, txt):
            return 'Found a match!'
        else:
            return 'Not matched!'
    string = input()
    print(match(string))

### OUTPUT

![image](https://github.com/user-attachments/assets/36be7008-8430-4305-b575-9a51c4bdc014)


### RESULT
Thus, the python program to find the pattern using regex has been implemented and executed successfully.
