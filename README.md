# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.
### Step 2: 
Open the existing file to read.
### Step 3: 
Open the new file to write.
### Step 4:  
Copy contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing and new file. Call the function.
### Step 6: 
End the program.
## PROGRAM:
#To write a python program for reading content from a CSV file.
#Developed by: THARUN SRIDHAR
#Register Number: 212223230230

with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)
    
### OUTPUT:
![image](https://github.com/Tharun0707/Copy-File/assets/145548496/b82bad8f-12b7-45e3-ad63-7143288839da)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
