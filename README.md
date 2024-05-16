# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values 
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: JANARTHANAN B
#Register Number: 212223100014

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![image](https://github.com/jokerjana/Word-Count/assets/147173630/25959359-d6ac-4fde-9d8b-2870e6f41ac7)


## RESULT:
Thus the program is written to find the word count from a text.
