# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open visual stdio

### Step 2: 
create file with py extension
 
### Step 3: 
start the program

### Step 4:  
write the code

### Step 5:
run terminal for output of the given program

### Step 6
end the program

## PROGRAM:
~~~
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:
      
    # read content from first file
    for line in firstfile:
               
             # append content to second file
             secondfile.write(line)
~~~            

### OUTPUT:
![](photo1.jpg)
![](photo2.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
