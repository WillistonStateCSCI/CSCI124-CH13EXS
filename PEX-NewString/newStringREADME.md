# Programming Example: newString
Chapter 8 discussed C-strings. Recall that:
1. A C-string is a sequence of one or more characters.
2. C-strings are enclosed in double quotation marks.
3. C-strings are null terminated.
4. C-strings are stored in character arrays.  

The only aggregate operations allowed on C-strings are input and output.  
To use other operations, the programmer needs to include the header file cstring,  
which contains the specifications of many functions for string manipulation. 
  
Initially, C++ did not provide any built-in data types to handle C-strings.  
More recent versions of C++, however, provide a string class to handle C-strings and operations on C-strings.  
  
Our objective in this example is to define our own class for C-string manipulation and, at the same time, to further illustrate operator overloading.   
More specifically, we overload the assignment operator, the relational operators, and the stream insertion and extraction operators for easy input and output.  

Enter the following line to compile:  
*g++ PEX-NewString/testMyString.cpp PEX-NewString/myStringImp.cpp -o PEX-NewString/newString*  
and the following line to execute:  
*./PEX-NewString/newString* 
