# python_assaignment

1) Add two numbers using python:

x = input("Type a number: ")
y = input("Type another number: ")
sum = int(x) + int(y)
print("The sum is: ", sum)
This program explains about how to add two number by asking input form the user.



2)python program to create star pyramid:

rows = int(input("Enter number of rows: "))
k = 0
for i in range(1, rows+1):
    for space in range(1, (rows-i)+1):
        print(end="  ")
   
    while k!=(2*i-1):
        print("* ", end="")
        k += 1
   
    k = 0
    print()
This program explains about how to form a pyramid using python, in this have used range function.we will just ask the user to enter the number of rows in which he want
to crete the pyramid.


3)python program to find random number and random character in a string:

import random
 list1 = [1, 2, 3, 4, 5, 6]
print(random.choice(list1))
 string = "striver"
print(random.choice(string))
This program exaplain about how to find a random number and random character in a string in this i have use random inbuilt function
random charactr means not a different character it is just a charecter which is unpredictable.


4)python program to find sum upto n natural numbers:

num = int(input('enter a number:'))
if num < 0:
   print("Enter a positive number")
else:
   sum = 0
   
   while(num > 0):
       sum += num
       num -= 1
   print("The sum is", sum)
   In this program we are finding the sum of the n natural numbers upto the user choice.
   
 
 5)python program to find the factorial of a number:
 
 num = int(input("Enter a number: "))
factorial = 1
if num < 0:
   print("Sorry, factorial does not exist for negative numbers")
elif num == 0:
   print("The factorial of 0 is 1")
else:
   for i in range(1,num + 1):
       factorial = factorial*i
   print("The factorial of",num,"is",factorial)
   IN this we have finded out the factorial of a given number by user. i have not used any recursive fuction here simply i used a for loop to 
   calculate the factorial of a given number.
   
   
 6)python program to find the given year a leap year or not:
 
 year = int(input("Enter a year: "))

if (year % 400 == 0) and (year % 100 == 0):
    print("{0} is a leap year".format(year))
    
elif (year % 4 ==0) and (year % 100 != 0):
    print("{0} is a leap year".format(year))

else:
    print("{0} is not a leap year".format(year))
    
    in this we have finded out the wether the given year is leap year or not by asking the input form the user.
    in this i have used theree conditions to find or check the given year is leap year or not.
    
    
  7)python program to find the given number is a prime number or not:
  
  
 flag = False
num=int(input('enter a number:'))

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    
    for i in range(2, num):
        if (num % i) == 0:
            
            flag = True
            break

    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")
        
        in ths i have finded out wether the given number is prime number or not using simple for
        loops and conditional statements.
        
        
 8)python program to find the lcm of a number :
 
 
 def compute_lcm(x, y):

   if x > y:
       greater = x
   else:
       greater = y

   while(True):
       if((greater % x == 0) and (greater % y == 0)):
           lcm = greater
           break
       greater += 1

   return lcm

num1 = int(input('enter the num1:'))
num2 = int(input('enter the num2:'))

print("The L.C.M. is", compute_lcm(num1, num2))

in this i have used functions to coompute theh lcm by taking the input form the use.



9)python program to reverse a number using while loop:

num = 1234
reversed_num = 0

while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num //= 10

print("Reversed Number: " + str(reversed_num))
in this program i have used while loop to find out the revese of a number.
used three condition.



10)finding square root of a number.

import math
print (math.sqrt(9))
print (math.sqrt(25))
print (math.sqrt(16))

in this i have used inbuilt sqrt function to compute the square root of a number we can also 
ask the uset to enter the number and pass the number into the sqrt function.



   
   
   
   
   
   
   
   
   
   
   
   
   
   
