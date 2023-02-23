#1.
#Write a program that asks the user to enter a character, checks, and prints whether the character is a consonant or a vowel.

a=input('Enter a = ')
if a in "aueiowyAEUIOWY": 
    print('the character is  a vowel')
else:
    print('the character is a consonant')
#2. 
#Write a program that asks the user to enter a number, checks, and prints whether the number is even or odd.

num = 0
print('Enter number:')
num = int(input())
if num % 2 == 0:
	print(num, 'is odd')
else:
	print(num, 'is even')

#3
#Write a program that asks the user to enter n number and prints the n-th Fibonacci number.

num= int(input("Enter number: "))
 
def Fibonacci(n):
    if n<= 0:
        print("Please enter positive number.")
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return Fibonacci(n-1)+Fibonacci(n-2)
print(Fibonacci(num))

#4.
#Write a program that asks the user to enter a number and prints the sum of its digits on the screen.

n=input("Enter number: ")
sum=0

for digit in n:
    sum=sum+int(digit)

print("Sum of digits",sum)


#5.
#Write program that prints the following image on the screen. Use cycles.
#	* * * * *
#       *       *
#       *       *
#	*       *
#	* * * * *
	
num = 5
for i in range(0, num):
    for j in range(0, num):
        if i == 0 or j == 0 or j == num-1 or i == num - 1:
            print("*", end=" ")
        else:
            print(" ", end=" ")
    print()

	
