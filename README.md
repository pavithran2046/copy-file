# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the source file in read mode.


### Step 2: 
Read the contents of the source file and store it in a variable
 
### Step 3: 
Close the source file.
### Step 4:  
Open the destination file in write mode. If the file doesn't exist, it will be created.
### Step 5: 
Open the destination file in write mode. If the file doesn't exist, it will be created.
### Step 6: 
Read the contents of the destination file and print it to verify the copy operation.
## step 7:
end the program
## PROGRAM:
```python
#program to copy the text file from one file to another file
#developed by pavithran
#register number 23001643
f=open(r"/content/drive/My Drive/zoro.txt","r")
a=f.read()
print(a)
b=open(r'/content/drive/My Drive/rorona.txt','w+')
b.write(a)
b.seek(0)
print(b.read())
```

### OUTPUT:
![output](/Screenshot%202023-07-27%20011250.png)
![output](/Screenshot%202023-07-27%20011408...1.png)
![output](/Screenshot%202023-07-27%20011502..2.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.