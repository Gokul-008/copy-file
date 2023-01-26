# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode
### Step 2: 
 Open the second file in append mode
### Step 3: 
Every word in first file is copied to second file using write()
### Step 4:  
close the first file
### Step 5: 
close the second file

## PROGRAM:
```
python program for copying the contents from one file to another file.
Developed by:Gokul.M
RegisterNumber: 22009089

f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
```

### OUTPUT:
![Screenshot (21)](https://user-images.githubusercontent.com/121165996/214904000-40b65ffb-1087-4048-8e9d-c3563982fdb4.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
