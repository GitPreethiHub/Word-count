# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file object to get file name from user.
### Step 2: 
 Open the file given by user.
### Step 3: 
Using the loop access the lines in file.
### Step 4:  
Use split function to seperate the words.
### Step 5: 
Count the number of words using len() function.
### Step 6: 
Print the number of words
## PROGRAM:
'''
Program to count the number of words in a file
Developed by: Preethi M
Register Number: 212222100037
'''
fp=input("Enter the file name:")
words=0
with open(fp,'r') as f:
  for line in f:
    word=line.split()
    words+=len(word)
print("Number of words:",words)
### OUTPUT:
![image](https://github.com/GitPreethiHub/Word-count/assets/119475585/abefa592-3b84-449e-8adf-db284e0403bc)

![image](https://github.com/GitPreethiHub/Word-count/assets/119475585/939f8fc3-2074-4dc1-bf4a-326f610f3ac6)

## RESULT:
Thus the program is written to find the word count from a text.
