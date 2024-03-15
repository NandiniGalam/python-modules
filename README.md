# python-modules
#math module
import math as m
result=m.sqrt(25)
print("square root of 25:",result)'''

from math import*
print(pi)
print(factorial(5))
print(sqrt(36))

import random
random_number=random.randint(1,10)
print("random Number:",random_number)'''


#random length of password
import random
passlen=int(input("enter length of password"))
s="abcdefghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
p="".join(random.sample(s,passlen))
print(p)


#system module
import sys
print(sys.path)

