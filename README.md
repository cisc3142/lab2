# Lab 2: Functions: templates, default arguments, specializations

Write a template function ```maxn()``` that takes as its arguments an array of items of type ```T``` and an integer representing the number of elements in the array and that returns the largest item in the array.


The number of elements should take the default value of 10.

The program should include a specialization that takes an array of strings as an argument and returns the longest string. (If there is a tie, the function should return the first one tied for longest.) (See http://www.cplusplus.com/reference/string/string/).

Test the function with an array of ten ```ints``` (using the default argument) and an array of four ```chars```. Test the specialization with an array of five strings.

## Deliverables:

   * A program called functions.cpp, which contains
   * A template function ```maxn()``` as described above
   * A specialization of ```maxn()``` which takes an array of strings as described above
   * A ```main``` function that 
      * declares an array of 10 ints, an array of 4 chars, and an array of 5 strings
      * passes each one to ```maxn()``` (with or without default arguments as appropriate)
      * prints the result of each call to ```maxn()``` (the largest element of each array) to the console

## Grading
The following factors will be part of this lab's grade:

   * Compilation: the code must compile (check Travis)
   * Style: indentation, variable naming, comments (make sure indentation survives uploading to github)
   * Compliance: all files and functions must be named as specified in the instructions, all output must look as specified
   * Correctness: all behavior specified in the readme must be implemented correctly

## Policies

### Collaboration
Discussion and working together is permitted. However, *submitted code must not be identical* and identical code will be considered plagiarism.

### Revision
Submissions may be revised until the due date, even after a pull request has been submitted, and even after an early submission has been graded.

