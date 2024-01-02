# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function as copy with arguments existing file, new file name.
### Step 2: 
Open a function to read. 
### Step 3: 
Open a function to write
### Step 4:  
Copy the contents from existing file to the new file.
### Step 5: 
End the program

## PROGRAM:
```
\*
# Program for copying contents from one file to another
# Developed by: V. Yogesh
# Register number: 212223230250
\*
def copy(fname,new):
  with open(fname,"r") as fp1:
    with open(new,"w") as fp2:
      data1=fp1.read()
      fp2.write(data1)
fname=input("Enter an existing file: ")
new=input("Enter name for the file: ")
copy(fname,new)
```
### OUTPUT:
![Screenshot 2024-01-02 215301](https://github.com/Yogesh-Yogi-1/copy-file/assets/148514598/bfbd5c8e-6d25-4dea-bd8b-89abdb8537bb)
![Screenshot 2024-01-02 220508](https://github.com/Yogesh-Yogi-1/copy-file/assets/148514598/373b4fff-9025-447b-9631-cb62c4c47319)
![Screenshot 2024-01-02 220559](https://github.com/Yogesh-Yogi-1/copy-file/assets/148514598/cd711f86-0e0e-43c0-a89f-d85310856aa7)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
