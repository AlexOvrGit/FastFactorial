# Fast Factorial
This project is a simple method to calculate a factorial or product of any segment
of an Arithmetic Sequence of positive natural numbers. The program uses only half the number of multiplications compared to the number of factors.
It is written in C#.

This is a partial class. The Main method should be
in another part of this class. One should provide the 
Main part to test or use this program.

I provide an example of the main part for your convenience. 
You will need any development environment to compile it with the program part.
It gets three parameters divided by spaces from the command line. 
If there are other parameters, it repeats.

Parameters:

All parameters are positive 32-bit (int) numbers.
 
Diff - difference between numbers:
  - factorial - 1,
  - double factorial - 2,
  - etc - what you need.
  
From - the first number:
  - factorial - 1,
  - double factorial - 1 or 2,
  - etc - what you need.
  
To - the last number:
 - (To - From) should be multiple of Diff.
 
Returns - BigInteger
 
