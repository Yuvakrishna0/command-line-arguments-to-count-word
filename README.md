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
```
Developed by: Yuva krishna k
Reg no: 212222110056

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```

### OUTPUT:
![Screenshot from 2023-06-10 19-13-07](https://github.com/Yuvakrishna0/command-line-arguments-to-count-word/assets/117915037/751d99f1-5ee6-4bd7-be80-ee9923ffea9d)
<br>
![Screenshot from 2023-06-10 19-13-15](https://github.com/Yuvakrishna0/command-line-arguments-to-count-word/assets/117915037/1e39399f-5070-43ba-818d-ead4f610816e)
<br>
![Screenshot from 2023-06-10 19-13-27](https://github.com/Yuvakrishna0/command-line-arguments-to-count-word/assets/117915037/20246194-22be-4861-9279-5d01f8f615d3)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
