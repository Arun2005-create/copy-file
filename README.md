# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content.
### Step 3:
 Read the file and close the file.
### Step 4: 
Now write the content in the new file.
### Step 5:
 When done print"File copied successfully".
### Step 6: 
End of the program

## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by : Arun Kumar B
#RegisterNumber:212223230021
with open("file.txt","r") as f:
    x=f.read()
with open("file1.txt","w") as f1:
    f1.write(x)
```
### OUTPUT:
![Screenshot 2023-12-29 180945](https://github.com/Arun2005-create/copy-file/assets/138849356/a3e3021f-6acc-47e8-8247-deaf13ccc44b)
![Screenshot 2023-12-29 181127](https://github.com/Arun2005-create/copy-file/assets/138849356/a27aa0b2-98aa-4b7f-9b48-4c3151bb9852)
![Screenshot 2023-12-29 181347](https://github.com/Arun2005-create/copy-file/assets/138849356/00916415-dc7e-4fc7-9810-74ce1faba8b9)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
