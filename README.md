# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open visual studio code or jupyter lab

### Step 2: 
create file with .py extension
 
### Step 3: 
also create .txt file and input sentences

### Step 4:  
write the code

### Step 5: 
run the program

### Step 6: 
print the values and end the program

## PROGRAM:
```python
#program for getting the word count from a text
#developed by:adhithiyan.k
#reference no:22001999
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
### OUTPUT:


![Screenshot_20230128_091220](https://user-images.githubusercontent.com/121029258/215275694-1c812782-caa6-4a02-8745-71fc5bf4075e.png)

## RESULT:
Thus the program is written to find the word count from a text.
