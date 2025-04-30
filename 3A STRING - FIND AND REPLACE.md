# Exp.No:3a
## STRING - CHECK PALINDROME

---

### AIM  
To write a python program to check whether an entered string is a palindrome or not without using built-in functions Available in Python

---

### ALGORITHM

1. Begin the program.  
2. Input the string from the user and store it in a variable string.
3. Check if the string is equal to its reverse (using slicing [::-1]).
4. If the string is equal to its reverse, print "The entered string is palindrome".
5. If the string is not equal to its reverse, print "The entered string is not palindrome".
6. Terminate the program.

---

### PROGRAM

    string = input()
    if (string[::] == string[::-1]):
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")

### OUTPUT

![image](https://github.com/user-attachments/assets/799bc976-e6e6-4c45-a48f-9e0a1bb2f80a)


### RESULT
Thus, the python program to check palindrome string is implemented and executed successfully.
