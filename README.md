# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open a text file as a read mode
### Step 2:
open another text file as a write mode
### Step 3:
Read a text file
### Step 4:
Write it in a text file
### Step 5:
End the program
## PROGRAM:
```
'''
To write a python program for copying the contents from one file to another file.
Developed by: Vikaash K S
Register number: 23013426
'''
with open("text1.txt","r") as f1:
    with open("text2.txt","w") as f2:
        a=f1.read()
        f2.write(a)
```
## OUTPUT:

### TEXT FILE:
![exp 5a tf](https://github.com/Vikaash19/copy-file/assets/148514589/6d5fbc5e-7240-4fb0-a653-7015c602ada3)

### COPIED FILE:
![exp 5a tf](https://github.com/Vikaash19/copy-file/assets/148514589/1cb8f5c0-9355-43c9-bce3-69efe76ee145)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
