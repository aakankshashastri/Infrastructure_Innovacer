# InnovaccerAssignment
## program in C++ (Linux OS)
## Problem Description:-
1. First problem is to find the top 10 biggest files from a Directory/whole system.
2. Second problem is to move the files from a source directory to folders according to their extensions to their destination directory.
## Functions Descriptions:-
For first problem :-
  ## scan_f()
      This function scans all the  exiting folders in given directory and sends the information of 
      files to put() function. 
  ## put() 
      This function inserts the information of files into a vector of size 10 according to increasing 
      order of size of files and by insertion sort it adds the files in vector. 
For second problem-
  ## Desk()
      Desk() function scanss all folders from source directory, finds the files and then sends the 
      path of files to move_file() function.
  ## move_file()
      move_file() function move files to folders according to their extensions into the destination
      directory and deletes files from source directory. 
## How to use:-
1. For first problem terminal asks the path of Directory or path of home. 
2. For second problem teminal ask two path, source directory path and destination directory path. 
