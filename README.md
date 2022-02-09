# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read access mode.

### Step 2: 
Intialize a variable with 0(word).
 
### Step 3: 
Iterate the content of the file using for loop.

### Step 4:
Split the contents into each line using .split() function.

### Step 5:
Iterate the list of lines and increment the value of variable (word) each time.

### Step 6:
End of the Program.

### PROGRAM:
```
#Program to coount the number of words in a file
#Developed By:S.S.Sanjay Kumar
#Register Number:21005845

with open('text.txt','r') as fp:
    count=0
    for data in fp:
        l=data.split()
        for i in l:
            count+=1
    print('Total No. of words in the file:',count)
```
### TEXT FILE:

![rec](./rec22.png)

### OUTPUT:
![rec](./rec12.png)


## RESULT:
Thus the program is written to find the word count from a text.
