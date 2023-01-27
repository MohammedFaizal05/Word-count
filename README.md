# Word-count
## AIM:

To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED:

PC Anaconda - Python 3.7
ALGORITHM:
## Step 1:

Open the file in read mode and handle it in text mode.
## Step 2:

Read the text using read() function.
## Step 3:

Split the text using space separator. We assume that words in a sentence are separated by a space character.
## Step 4:

The length of the split list should equal the number of words in the text file.
## Step 5:

You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
## Step 6:

Finally,print the number of words and display the output.
## PROGRAM:

```python
#Program to find the gcd of a number using function.
#Developed by: Mohammed Faizal.J
#RegisterNumber: 22003412
num_words = 0
with open ('myfile.txt','r') as file1:
    for i in file1:
        word = i.split()
        num_words +=len(word)
print("Number of words ={}".format(num_words))
```

### OUTPUT:
![c](https://user-images.githubusercontent.com/120553195/214854434-073482ee-f3d4-4381-9f23-dc34e7242d1b.png)
![w](https://user-images.githubusercontent.com/120553195/214854466-fc61be9a-10ce-465c-97da-cad916b5bdcc.png)



## RESULT:
Thus the program is written to find the word count from a text.
