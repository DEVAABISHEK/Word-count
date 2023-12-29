# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file using notepad with extension txt
### Step 2: 
 open google colab and mount the drive for using the created file
### Step 3: 
now open the text file in read mode
### Step 4:  
then read and split the file using the read() and split() which is assigned to the variable
### Step 5: 
print the assigned variables length using len() funcion
### Step 6: 
end of the program
## PROGRAM:
#count the number of words in a text file
#developed by:DEVA ABISHEK P
#register number: 23012976
with open('/content/drive/MyDrive/record/content.txt','r') as f:
  a=f.read().split()
  print(len(a))
### OUTPUT:
1.TEXT FILE:

<img width="663" alt="292661376-d2ff1c55-9932-4e18-bc8d-0858ca18b790" src="https://github.com/DEVAABISHEK/Word-count/assets/150319305/91c8f898-598e-41fe-8a94-ce73df9c5885">

2.MOUNT DRIVE:

![292661434-6445739b-839c-46dd-809d-5eb54f424f64](https://github.com/DEVAABISHEK/Word-count/assets/150319305/deec775f-c324-49ce-b8df-f6ada3a67058)

3.OUTPUT:

![292661456-7feb2aca-9506-42bd-83dc-fb76e821e7cf](https://github.com/DEVAABISHEK/Word-count/assets/150319305/67196eb4-1e92-4fc5-a51c-5de9897cd7e3)


## RESULT:
Thus the program is written to find the word count from a text.
