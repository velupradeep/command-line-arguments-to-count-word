# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1::import sys

### Step 2:  initially make count = 0
 
### Step 3:  open the content file using command line arguments.

### Step 4:  by using for loop name the function as "line" 

### Step 5:  split the line using .split

### Step 6:  split the line using .split

## PROGRAM:
```
import sys
fp=open(sys.argv[-1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```

### OUTPUT:
![py5 2](https://github.com/velupradeep/command-line-arguments-to-count-word/assets/150329341/dc422875-4c35-4a5b-9134-b543f842a30d)
![5 22](https://github.com/velupradeep/command-line-arguments-to-count-word/assets/150329341/16449377-41fa-4c85-8203-adf240e9def9)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
