# Word-count
### NAME: SHYAM.S
### REG.NO: 23012478
### DEPT: AIML
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
To write a python program for getting the word count from a text file.

### Step 2: 
Open the required file by using the function "with".

### Step 3: 
Then use the laptop to assign the i value in the file.

### Step 4:  
Using split function to spilt the words.

### Step 5: 
Finding the given length of the words by using len() fuction.

### Step 6: 
Calling the function and Printing the number of words.

## PROGRAM:

```
#Program to find the Word Count
#Developed by: SHYAM S
#Register Number: 23012478
num=0
with open("shyam.txt","r") as file:
    for i in file:
        word=i.split()
        num=num+len(word)
print("The number of words are in the file is:",num)
```

## OUTPUT:

![Screenshot 2024-01-02 143344](https://github.com/SridharShyam/Word-count/assets/144871368/1bd925aa-0bf6-4509-b812-62b440dcab28)

## RESULT:
Thus the program is written to find the word count from a text.
