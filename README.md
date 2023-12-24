# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
'''
Developed by : P.Jeshwanth Kumar
Registered number : 212223240114
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![image](https://github.com/Jeshwanthkumarpayyavula/command-line-arguments-to-count-word/assets/145742402/09a49b8c-e78a-4184-97bd-bf8e053bcc99)
![image](https://github.com/Jeshwanthkumarpayyavula/command-line-arguments-to-count-word/assets/145742402/f7540110-9092-4e7b-9b53-5b581fc8d6d3)

![Screenshot 2023-12-24 125547](https://github.com/Jeshwanthkumarpayyavula/command-line-arguments-to-count-word/assets/145742402/bb8f1ff7-354f-4cc9-a41a-6bf8630fda90)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
