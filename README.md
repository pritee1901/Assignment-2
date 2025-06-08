

# Even and Odd Number

'''
Problem Statement:  Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.
'''


a=int(input('enter a number:'))
if a%2==0:
    print(' is a even number')
else:
    print(' is a odd number')




  '''
    Problem
    Statement: Write a Python program that:
    1. Uses a for loop to iterate over numbers from 1 to 50.
    2.calculate sum of all interger range 
    3.display final sum.
'''

total=0
for i in range(1,51):
    total += i
    print('sum of numbers from 1 to 50 is: ',total)
