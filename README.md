# python-internship-task_9


1.Create a lambda function that multiplies argument x with argument y

mul = lambda x,y: x*y

print(mul(2,3))

2.Write a Python program to create Fibonacci series to n using Lambda

def fibonacci(count): 

    x= [0, 1]

    any(map(lambda _: x.append(sum(x[-2:])),range(2, count)))

    return x[:count]   

print(fibonacci(10))

3.Write a Python program that multiply each number of given list with a given number 

num=[2, 4, 6, 9 , 11]

n=2

print("Original list:", num)

print("Given number:", n)

Mlist=map(lambda number:number*n,num)

print(' , '.join(map(str,Mlist)))

4.Write a Python program to find numbers divisible by 9 from a list of numbers

list_1=[9,18,27,35,42,55,36,45]

res=list(filter(lambda x:(x%9==0),list_1))

print("the no divisible by 9 are ",res)

5.Write a Python program to count the even numbers in a given list of integers

list_1=[2,4,6,9,7,5,10]

even=len(list(filter(lambda x :(x%2==0),list_1)))

print("even no's in the list are:",even)

