# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Mount your colab with your drive

## Step 2:
Open your text file in python code runner.

## Step 3:
Read the file and split the words separately using split().

## Step 4:
Count the number of words in text file using for() loop.

## Step 5:
End the program


## PROGRAM:
```python
#Program to for getting the word count from a text.
#Developed by:VIGNESH.V
#Register Number:23004027
from google.colab import drive
drive.mount('/content/drive')

f=open('/content/cars (1).csv','r')
b=f.read()
d=0
c=b.split(' ')
for i in c:
  d=d+1
print('The number of words:',d)
```

### OUTPUT:
![Screenshot 2024-01-02 161913](https://github.com/23004027/Word-count/assets/138956447/9a1afe63-6972-4122-a007-3fccab2ee54d)
![Screenshot 2024-01-02 161933](https://github.com/23004027/Word-count/assets/138956447/540f736c-0b7b-43bd-ad67-8462a5843610)




## RESULT:
Thus the program is written to find the word count from a text.
