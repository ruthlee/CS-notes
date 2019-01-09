# NOTES FOR C (ahem, For Future Reference) 

The workflow here is: write the program using vim, compile it, then run it. Let's take a look at the "hello world" C program: 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1 #include <stdio.h>
2 int main()
3 {
4 	printf("%s\n", "hello world.\n");
5 	getchar();
6 	return 0;
7 }

~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I've included the line numbers for easy reference. 

Let's take apart what each line does.

**Line 1 : Header**
Allows us to access standard functions that come with the compiler. 
#include tells the compiler to put in the code from "stdio.h" into the program before creating everything else (ie, our main function). This seems similar to importing libraries in Python (albeit more primitive). 

**Line 2: "main" function**
Whenever a program first executes, the main function executes first. Other functions are called within the main function.

**Line 3, Line 7: Brackets**
It would probably be bad to forget these :) They signal the beginning and end of functions (not as simple as in Python, alas)

**Line 4: printf**
Standard command to print. \n signals new line.

**Line 5: getchar()**
This is a function that reads in a single character that the user inputs. User must hit enter before the program will read the character. Apparently this line is here so that we have time to see what the program does. As it turns out, it's not super necessary with the gcc compiler because we actually create an executable file which shows us the output. 

**Line 6: return statement**
This is important because "it can be used to tell the OS whether the program succeeded." Apparently 0 means success. Hopefully this will make more sense in a bit.  


## COMPILING AND RUNNING A PROGRAM

Wow this is important. Whenever we make a program (let's say the program name is myprogram.c) these are the steps to follow: 

 1) Go to the directory of the program and type "gcc myprogram.c". This compiles your program. (thing to test: does anything go wrong if you compile two programs at once? What happens if you do that and run them at the same time?)

 2) Now we have to run the program by creating an executable. You can do do this by typing "./a.out" 
