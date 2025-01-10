**Command line argument
**
to make the program **runtime**, instead of hardcoding the values while calling the function we send the values during program execution. 

In Python, **sys** is a built-in module that provides access to some variable and functions that interact with the python runtime environment. It is part of Python standard library, so you don't need to install anything to use it.


**sys.argv**

import sys

num1 = int(sys.argv[1])
num2 = int(sys.argv[2])


python3 program.py 2 3



**Environment Variable 
**
to store any sesitive information like password, API keys, Token, Certificates, we make use of environment variable 
cmd : env --> gives inbuilt env variables

import os
print(os.getenv("password"))

export password="amrita" ----> this is how we set env variable

**Python getpass module
 **

 When we use terminal based application with some security credentials that use password before execution the application, Then It will be done with Python Getpass module. In this article we are going see how to use Getpass module.

Getpass module provides two function:

getpass.getpass()
getpass.getuser()

import getpass 
  
pwd = getpass.getpass(prompt = 'Enter the password') 
if pwd == 'Admin': 
    print('Unlock!') 
else: 
    print('You entered wrong password') 
