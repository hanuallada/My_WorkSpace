
In programming like C, C++ and Java, we use {} brackets to represent a group of code or module

But in ==**Python indentation**== (4 spaces or 1 tab) represents a group of logic.

for i in range(10):
	print(i)

if any issues in the code indentations then Error: unindent doesn't match any outer indentation level

if True:
	print("Learning python is easy")
	a="Data Analytics"
	print(a)

to execute multiple line statements in one line

if True: print("Learning python is easy"); a="Data Analytics"; print(a)

==**Multiline statement**==

Writing same statement in multiple lines instead of single line just like SQL query columns in select query

give \ at the end of each line to consider as one statement or Keep everything in between ( and ).

Hanu= 1 + 2 + \
		3 + 4 + \
		5 + 6
Hanu =  ( 1 + 2 +
		3 + 4 + 
		5 + 6 )
print(Hanu)

==**Variable**==

A variable is  a named storage location that stores data or values.
variables are used to represent and manipulate data in a program
when you create a variable, you are essentially assigning a name to particular value or data type

a = 10
b = 20
c = 30

the above can be represented by below
a=10; b=20; c=30 
a, b, c = 10, 20, 30

age=25
print("My age is ", age, "years old")

print(id(a))
returns the storage ==location== where 25 is stored