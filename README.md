# HLA (High Level Assembly) Examples


##### Documentation: http://tux.cs.unlv.edu/hla/HLARef_html/HLARef.html
##### HLA Download Page: http://www.plantation-productions.com/Webster/HighLevelAsm/dnld.html
##### Webpage for MASM: http://www.masm32.com/

### 1. sumInputs
Write a program named sumInputs (in a file named sumInputs.hla) that reads a list (see hints section below) of positive numbers from the user until the user enters zero. Display the sum of the positive integers read. All the values you read from the user and manipulate in the program must be unsigned 8-bit integer quantities (use getu8()). You may assume all inputs are less than 256.

### 2. BinaryFPRep

Create a program named BinaryFPRep.hla that does the following:

Reads a floating point value from the user and displays this value in the following formats:

a) Decimal scientific notation (use pute64()),

b) As a 64 bit unsigned hex number,

c) As 64 binary digits. Separate each nibble with a ‘_’ character, separate the sign, exponent and mantissa bits from each other with spaces.