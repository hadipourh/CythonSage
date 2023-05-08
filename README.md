# CythonSage
An example of using an external C code in Python (SageMath)

This project shows, how to use Cython to embed a C code within a python project. Let we are given a C code implementing some functions
efficiently, and we want to use it in a bigger project which is written in Python language. 

Here the C code has been taken from  [KeeLoq](https://github.com/hadipourh/KeeLoq), which is a C implementation of a 
block cipher called KeeLoq, and we want to use it in our Python project. 

Do the following steps to run the project: 

Clone the project:
    
    git https://github.com/hadipourh/CythonSage.git
    cd CythonSage/

Use the SageMath to open the ``Cythonized KeeLoq.ipynb`` file: 
   
    sage -n jupyter Cythonized\ KeeLoq.ipynb
   
Enjoy playing with the code!
