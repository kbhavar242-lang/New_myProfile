name = input ("Enter Name: ")
print (name)
print (type (name))

i = int (input ("Enter any integer: "))
print (i)

print (type (i))

f = float (input ("Enter any floating number: "))
print (f)
print (type (f))

b = bool (input ("Is 2 + 2 = 4 ? State True or False: "))
print (b)
print (type (b))

=================================================================================================================================================

a = int (input ("Enter number a: "))
b = int (input ("Enter number b: "))
print ("Sum of a & b: ",(a+b))

c = int (input ("Enter number c: "))
d = int (input ("Enter number d: "))
print ("Subtraction of d from c: ",(c-d))

=================================================================================================================================================

a = int (input ("Enter value of a: "))
b = int (input ("Enter value of b: "))

if a > b :
    print ("a is greater than b")
elif b > a :
    print ("b is greater than a")
else :
    print ("a and b are equal...")
    
if a >= 90 :
    print ("Topper")
elif a >= 70 :
    print ("Good")
elif a >= 50 :
    print ("Average")
else :
    print ("Fail")

=================================================================================================================================================

for i in range (6) :
    print (i)

print ()

for j in range (1,6) :
    print (j)

print ()
    
for k in range (3) :
    print ("Hello")
    print (k)
    
print ()
    
for l in range (1,3) :
    print ("Hello")
    print (l)

=================================================================================================================================================

name = input ("Enter Student's Name: ")
print ("Entered Name:",(name))
print (type(name))
print ()

marks = int (input ("Enter Student's Marks: "))
print ("Entered Marks:",(marks))
print (type(marks))
print ()

if marks >= 75 :
    print ("Distinction")
elif marks >= 60 :
    print ("First Class")
elif marks >=40 :
    print ("Passed")
else :
    print ("Fail")

=================================================================================================================================================

n = int (input ("How many times you want to enter the no.?: "))
print ("Entered n:",n)
print ("Type of entered n:",type(n))
print()
for i in range (n) :
    num = int (input ("Enter number: "))
    print ("Entered num:",num)
    print ("Type of entered num:",type(num))

    if num > 0 :
        print ("Entered no. is positive")
    else :
        print ("Entered no. is negative")
    
    print()

=================================================================================================================================================
