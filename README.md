# FOSS-2-
FOSS PRACTICAL NO. 2 
                   Practical no. 2
Aim =  Script and interactive modes: defining a function in the two modes: executing a script: interactively executing a statement list (semicolon separated statements): the input function.
>>> def displaywelcomec():
	print("Good Morning")
	print('Welcome')
>>> displaywelcomec()
Good Morning
Welcome
>>> def displaynum():
	a=10
	print("value of a",a)

	
>>> displaynum()
value of a 10
>>> def display(num):
	return num

>>> display(10)
10
>>> def add(m,n):
	return m+n

>>> add(10,12)
22>>> def sub(m,n):
	return m-n

>>> sub(20,8)
12
>>> def mult(m,n):
	return m*n

>>> mult(8,12)
96

>>> def div(m,n):
	return m/n

>>> div(12,48)
0.25
>>> def square(m):
	return m**2

>>> square(6)
36

>>> def areaofcircle(r):
	return 3.14*r**2

>>> areaofcircle (4)
50.24
>>> def areaofrectangle(l,b):
	return l*b

>>> areaofrectangle (4,5)
20
>>> def convertf(c):
	return (c*9/5)+32

>>> convertf(38)
100.4
>>> def convertcel(f):
	return (f-32*5/9)

>>> convertcel(102)
84.22222222222223
>>> def avg(m,n,o):
	return (m+n+o/3)

>>> avg(5,6,7)
13.333333333333334
>>> def name(s):
	return s

>>> name('Priya')
'Priya'
>>> def convertcm(m):
	return 100*m

>>> convertcm(3)
300
>>> def convertm(n):
	return n/100

>>> convertm(5)
0.05


2.2 : Semicolon Separated Statements 
>>> 2+3; 4**2; 4-2
5
16
2
49
>>> print('hello'); round(49.38); x=10; print(x)
hello
49
10

>>> 100//3; x=None; print("The value of x is",x)
33
The value of x is None


2.3 :  Use Input function
 
num1= int(input("Enter number"))
num2=int(input("Enter number"))
multiplication= num1*num2
print("Multiplication=",multiplication)
division=num1/num2
print("Division=",division)
substraction=num1-num2
print("Substraction=",substraction)    
output:
>>> 
Enter number4
Enter number8
Multiplication= 32
Division= 0.5
Substraction= -4
Program

