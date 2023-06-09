# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import sys module.

Step 2:
Open the file with sys.argv[1].

Step 3:
Use the for loop to select the content in file.

Step 4:
Use split function to to separate the file content into words or strings.

Step 5:
Count the length of the words using len.

Step 6:
Print the number of words.

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments.
Programmed by: M.CHANDRU
Ref.No.: 212222230026

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:

![image](https://github.com/chandrumathiyazhagan/command-line-arguments-to-count-word/assets/119393023/a41544e5-3004-4ae3-be96-c8b2e9810798)
![image](https://github.com/chandrumathiyazhagan/command-line-arguments-to-count-word/assets/119393023/3988feeb-892a-4e5e-a948-b2df5b2e828d)
![image](https://github.com/chandrumathiyazhagan/command-line-arguments-to-count-word/assets/119393023/588db9f1-08e0-40f5-9a3c-6c058364d78e)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
