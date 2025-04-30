# Exp.No:3c
## LIST - REVERSE THE MEMBERS OF A LIST

---

### AIM  
To Write a python program to reverse the members of a given list

---

### ALGORITHM

1. Begin the program.  
2. Input the integer n which represents the number of elements in the list.
3. Initialize an empty list input_list.
4. Use a loop to input n integers and append each to input_list.
5. Use a loop to iterate through the first half of the list (n // 2 times).
6. Inside the loop, swap the elements at positions i and n-i-1.
7. After the loop, print the modified input_list (which has been reversed).
8. Terminate the program.

---

### PROGRAM

      n=int(input())
      input_list=[]
      for i in range(0,n):
          input_list.append(int(input()))
      for i in range (n//2):
          #Add your code
          temp = input_list[i]
          input_list[i] = input_list[n-i-1]
          input_list[n-i-1] = temp
      print(input_list)


### OUTPUT

![image](https://github.com/user-attachments/assets/d3ce0884-3d14-4c19-9464-70fb480a65ac)

### RESULT
Thus, the python program to reverse the members of a given list has been implemented and executed successfully.
