# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a text file in read mode.
### Step 2: 
Open another file in append mode.
### Step 3: 
Using for loop append the text in the first file to the second file

## PROGRAM:
```Python
with open("helo.txt",'r') as f1:
    with open("hi.txt",'a') as f2:
       for line in f1:
           f2.write(line)
```

### OUTPUT:
![image](./Screenshot%20from%202023-01-28%2014-22-27.png)
![image](./Screenshot%20from%202023-01-28%2014-22-09.png)
![image](./Screenshot%20from%202023-01-28%2014-22-02.png)
![image](./Screenshot%20from%202023-01-28%2014-24-36.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.