# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create another text file to copy
### Step 2: 
now open both file using with open()
### Step 3: 
now read the file and the write on another file using read() and write()
### Step 4:  
now excuete the program
### Step 5: 
now check the another file to see its copied
### Step 6: 

## PROGRAM
```
#Program for copying the contents from one file to another file
# developed by: franklin raj G
# register no: 23001518
def copy(fname,newfile):
     with open(fname,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("enter an existing file:")
newfile=input("enter a name for anew file:")
copy(fname,newfile)

```

### OUTPUT:
![Screenshot 2024-01-03 003558](https://github.com/franklinraj/copy-file/assets/148993740/557393dc-822b-404b-bf5e-0719edd2dd6e)
![Screenshot 2024-01-03 003612](https://github.com/franklinraj/copy-file/assets/148993740/0e651ed5-c245-4907-851e-bfcbaee4996f)
![Screenshot 2024-01-03 003621](https://github.com/franklinraj/copy-file/assets/148993740/b0012eb8-38e8-48fc-a6dd-689186f42055)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
