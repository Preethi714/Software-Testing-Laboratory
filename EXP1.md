# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
def display():
    start=input("Enter a positive value for START:")
    end = input("Enter a positive value for END:")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end='')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()

def display():
    start=input("Enter a positive value for START:")
    end = input("Enter a positive value for END:")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end='')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()

def display():
    start=input("Enter a positive value for START:")
    end = input("Enter a positive value for END:")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end='')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()

def compare():
    a=input("Enter a value for A:")
    b=input("Enter a value for B:")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

def iterate():
    string=input("Enter a string:")
    for i in string:
        print(ord(i),end=" ")
iterate()
### Output:
![Screenshot 2025-03-13 092712](https://github.com/user-attachments/assets/a1589c06-4636-4ad1-ac07-28cfbd75bde0)
![Screenshot 2025-03-13 090616](https://github.com/user-attachments/assets/44a923b2-a9cf-404c-bdc3-245c16e5acb9)

![Screenshot 2025-03-13 091054](https://github.com/user-attachments/assets/a49646ad-dbf5-4b98-9b2a-53ab0d4c3908)

![Screenshot 2025-03-13 091616](https://github.com/user-attachments/assets/bb6dbe82-07d9-49b3-b70b-73274b809027)

![Screenshot 2025-03-13 092424](https://github.com/user-attachments/assets/c63a5c9d-c907-4366-b67b-1d1aeaabf73f)

![Screenshot 2025-03-13 092712](https://github.com/user-attachments/assets/05cfa86e-f3d5-4248-b10c-a383d16e1262)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


