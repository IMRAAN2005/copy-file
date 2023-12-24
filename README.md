# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
Developed By:DSHAIK MAHMMAD IMRAAN
Register No: 212223100053
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![image](https://github.com/IMRAAN2005/copy-file/assets/149347407/dce78c70-17d1-497f-9c08-a00db9644546)
### Copied File:
![image](https://github.com/IMRAAN2005/copy-file/assets/149347407/394d6afc-3e29-4507-a845-196dc8e92f22)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
