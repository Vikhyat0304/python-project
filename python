import random as r
a=int(input("Enter lower limit: "))
b=int(input("Enter upper limit: "))
def pos_neg(n):
    if n>0:
        print(n,"is a positive number")
    elif n==0:
        print(n,"is neither positive nor negative")
    elif n<0:
        print(n,"is a negative number")
def odd_even(n):
    if n%2==0:
        print(n,"is an even number")
    elif n%2!=0:
        print(n,"is an odd number")
def prime_comp(n):
    if n>1:
        for i in range(2,n//2 +1):
            if n%i==0:
                print(n,"is a composite number")
                break
        else:
            print(n,"is a prime number")
    else:
        print(n,"is neither prime nor composite")
n=r.randint(a,b)
pos_neg(n)
odd_even(n)
prime_comp(n)
