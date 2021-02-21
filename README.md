In this tutorial, we will learn what are <a href="https://usemynotes.com/what-are-header-files-in-c/">header files in c</a> programming and the types of header files, and how to use header files.  So let us go into the deep models.

## What are header files in c?

Header files are those files in which c functions declaration and macro definitions are shared between various source files. By using the header files we can save time as the program becomes short and readable. There are two types of header files built-in header files and user-defined header files. 

The header files serve two purposes: first, the system header files declare the interface to the parts of the operating system. They help in supplying the definition and declaration needed for invoking the system calls and libraries. Secondly, the header files contain the declaration for interfaces between the source files of the program.

All the header files have a ‘.h’ extension. This extension contains a c function declaration and the macro definitions. The header files can be requested using the preprocessor directive which is #include.
 
## What are the types of header files?
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6dqppce8mb35uz0exiyn.png)

There are 2 types of header files

<table>
<ul>
<li>Built-in the header file</li>
<li>User-defined header file</li>
</ul>
</table>

### Built-in header file

This is the header file that is provided by the compiler. We can not change anything in the built-in header files. Header files provide the basic functionality. 

<b>For example -</b>
```
    #include <stdio.h>
    #include <math.h>
    #include <string.h>
    #include <stdlib.h>
    #include <time.h>
    #include <ctype.h>
    #include <conio.h>
    #include <float.h>
```
 
### User-defined header file

The User-defined header files are defined by the user. These are created using the file program. The user-defined header files are like the built-in header file.

<b>For example:</b> #include “File_name.h”

 
## How to use header files?

To use these Header files in a program we have to use the #include directive. Whenever we want to include built-in header files we write < > (angle brackets).

----

-Learn into deep - <a href="https://usemynotes.com/what-are-header-files-in-c/">Header Files in C</a>


