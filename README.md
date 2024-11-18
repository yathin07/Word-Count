## DATE:
## Ex No 9 - Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0.
### Step 2: 
Open it with txt file.
### Step 3: 
Give range for i.
### Step 4:  
Then next split the words.
### Step 5: 
Count the number of words.
### Step 6: 
Giving print statement for getting output.
## PROGRAM:

```

#Program for getting the word count from a text

num_words =0
with open('text.txt','r') as file1:
 for i in file1:
  word =i.split()
  num_words += len(word)
print("Number of words={}".format(num_words))






```
### OUTPUT:
![image](https://github.com/user-attachments/assets/9d275196-ef3b-4d00-b027-919441de6c23)

![image](https://github.com/user-attachments/assets/152bf73d-0d45-44a7-8134-276bac74497b)


## RESULT:
Thus the program is written to find the word count from a text.
