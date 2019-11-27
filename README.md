# Hackerrank
Day 3: Intro to Conditional Statements
#Task
#Given an integer, , perform the following conditional actions:

#If  is odd, print Weird
#If  is even and in the inclusive range of  to , print Not Weird
#If  is even and in the inclusive range of  to , print Weird
#If  is even and greater than , print Not Weird

#Input Format
#A single line containing a positive integer, .

#Constraints
## 1 <= n <= 100


#Output Format
#Print Weird if the number is weird; otherwise, print Not Weird.


#!/bin/python

import sys
import math

n = int(input())

if n % 2 == 1:
    print('Weird')
elif n % 2 == 0 and n in range(2,5):
    print('Not weird')
elif n % 2 == 0 and n in range(6,20):
    print('Weird')
else:
    print('Not weird')
