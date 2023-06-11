# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
 Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
Program for getting the word count from the contents of a file using command line arguments
Developed by: Sanjay G
RegisterNumber: 212222230131

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)

### OUTPUT:
![image](https://github.com/Sanjay-sg/command-line-arguments-to-count-word/assets/119559022/522eb51f-d832-4fde-a82a-237aa448491e)
![image](https://github.com/Sanjay-sg/command-line-arguments-to-count-word/assets/119559022/b0d10d11-074c-472c-9cc9-9f1ce5d69770)
![image](https://github.com/Sanjay-sg/command-line-arguments-to-count-word/assets/119559022/ad9ee9af-a7b5-472c-b88e-82c1482d8c20)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
