
 [2]:

print("To find the maximum of three numbers") Max=0 a=float(input("Enter the first number:")) b=float(input("Enter the second number:")) c=float(input("Enter the third number:")) if(a>=b) and (a>=c): Max=a elif(b>=a) and (b>=c): Max=b else: Max=c print("The Maximum of three is",Max) 

To find the maximum of three numbers Enter the first number:5 Enter the second number:8 Enter the third number:4 The Maximum of three is 8.0 

In [7]:

print("To reverse a string") def reverse(s): str=" " for i in s: str=i+str return str s=str(input("Enter the string:")) print("The original string is:",s) print("The reversed string is:",reverse(s)) 

To reverse a string Enter the string:Python Development The original string is: Python Development The reversed string is: tnempoleveD nohtyP 

In [4]:

flag=0 i=0 n=int(input("Enter a positive integer:")) for i in range(2,n): if n%i==0: flag=1; break; if n==1: print("1 is neither prime nor composite") else: if flag==0: print(n,"is a prime number") else: print(n,"is not a prime number") 

Enter a positive integer:29 29 is a prime number 

In [5]:

print("To find the sum of squares of first n natural numbers") def sumsquare(n): return((n*(n+1)*(2*n+1))/6) n=int(input("Enter the value of n:")) print(sumsquare(n)) 

To find the sum of squares of first n natural numbers Enter the value of n:6 91.0 

In [8]:

num = input('Enter any number : ') try: val = int(num) if num == str(num)[::-1]: print('The given number is PALINDROME') else: print('The given number is NOT a palindrome') except ValueError: print("That's not a valid number, Try Again !") 

Enter any number : 5005 The given number is PALINDROME

