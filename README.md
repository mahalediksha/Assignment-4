# Assignment-4

Code:

def prime_or_not(num):
  if num > 1:
   for i in range(2,num):
     if (num % i)== 0:
       print ("Given number is not a prime number")
       break
     else:
       print ("Given number is a prime number")
       break
  else:
    print ("Given number is a prime number")

Output:

prime_or_not(7)
Given number is a prime number
