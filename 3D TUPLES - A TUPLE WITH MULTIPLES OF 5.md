# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 9

---

### AIM  
To write a Python program to create a tuple containing all multiples of 9 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Input the integer n, which determines the limit for the tuple.
3. Initialize an empty tuple t.
4. Set num to 9.
5. Use a while loop to add multiples of 9 to the tuple t until num is greater than or equal to n.
   - In each iteration, add num as an element to the tuple.
   - Increment num by 9 after each iteration.
6. After the loop, print the tuple t.
7. Print the length of the tuple using len(t).
8. Terminate the program.

---

### PROGRAM

    n = int(input())
    t = tuple()
    num = 9
    while(num<n):
        t = t + (num,)
        num = num + 9
    print(t)
    print("Length of the tuple is",len(t))

### OUTPUT

![image](https://github.com/user-attachments/assets/1e86aecf-be9f-4336-9ccb-d3545abed9a1)


### RESULT
Thus, the python program to create a tuple containing all the multiples of 9 up to 'N' has been implemented and executed successfully.
