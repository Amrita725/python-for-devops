Command line argument

to make the program **runtime**, instead of hardcoding the values while calling the function we send the values during program execution. 

In Python, **sys** is a built-in module that provides access to some variable and functions that interact with the python runtime environment. It is part of Python standard library, so you don't need to install anything to use it.


**sys.argv**

import sys
num1 = int(sys.argv[1])
num2 = int(sys.argv[2])


python3 program.py 2 3

 
