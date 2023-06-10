# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM:

Step 1:

First we need to open the required the from which we need to copy the text.

Step 2:

Using keyword "with" to open the required file.

Step 3:

Again using the with keyword to open the empty file.

Step 4:

The empty file is open by using 'W' which is used to write only.

Step 5:

The for function is used to take each line from the main file.

Step 6:

Write() is used to write the lines of main file to the empty file or to the directed file.

## PROGRAM:
```
with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
Text File:
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
Empty File:
with open("data.txt","w") as fd:
 fd.write("")
Copyed file:
with open("data.txt","r") as f2:
  data1=f2.read()
  print(data)
```
## OUTPUT:
![5c1](https://github.com/yogeshrao05/copy-file/assets/122008288/4acdeb36-ec79-437a-b798-78bee8e314b4)
![5c2](https://github.com/yogeshrao05/copy-file/assets/122008288/cae4d99a-2334-4814-bd6d-86ab7532e3a3)
![5c3](https://github.com/yogeshrao05/copy-file/assets/122008288/f7cc81b9-0b8f-4315-b248-43f417e7839c)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
