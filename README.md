# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file object and get file name from the user

### Step 2: 
Open the file given by the user
 

### Step 3: 
Using for loop access the file

### Step 4:  
Use split funtion to separate the words

### Step 5: 
The words is then counted by len function

### Step 6: 
Print the number of words

## PROGRAM:
```
'''
Program to count the number of words in a file
Developed by :S.ROSELIN MARY JOVITA
Register number: 212222230122
'''

fp=input("Enter the file name:")
words=0
with open(fp,'r')as f:
    for line in f:
        word=line.split()
        words+=len(word)
print("Number of words: ",words)
```



### OUTPUT:

 ![WORD COUNT1](https://github.com/Roselinjovita/Word-count/assets/119104296/16e99051-700b-4b0d-96aa-cfd7b3ee8864)

 
 
 ![WORDCOUND2](https://github.com/Roselinjovita/Word-count/assets/119104296/2eb495aa-565f-4c3d-a0bb-1aa8a23fcb14)



## RESULT:
Thus the program is written to find the word count from a text.
