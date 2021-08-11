# PosixThreadpoolexampleForGithub
Simple Threadpool framework using posix thread, mutex and conditional variable.

1.This threadpool framework is created using posixthread currently
created 4 worker thread(Hardcode in Threadpool_main.cpp) you can increase it as per your requirement.
2.Main thread add data into queue and notify worker thread so one of worker thread wake up and process data.
3.Finally Denit is called to deallocate and all the resources.
4.If you want to remove hardcodecoding then you can modify main of this program

Steps to run given program
step1:
  make all 
step2:
  ./a.out
  
How to use this framework in your code.
Step1: 
Create object of cEventThreadlPool this class

Step2:
Call Init method of cEventThreadlPool this class
i/p
a) Number of worker thread you want to create
b) Pass address of function that you want to call by worker thread.

Step3:
  Call Deinit of cEventThreadlPool class.
   
