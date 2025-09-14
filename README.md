# Data-Structure-and-Algorithms-Python-Practice-
This is my Python-based project focused on solving Data Structures and Algorithms problems to strengthen my coding skills, improve my problem-solving abilities, and to deepen my understanding of CS core concepts.

# What I learned: 
- I have practiced and improved my coding skills through uisng loops, conditionals and functions in Python
- I learned to manage, use, upload, document and organise code on Github
- I have deepened and strengthened my understanding in CS concepts

# Skills Used: 
- Python
- Problem-Solving
- Version with Git and Github
- Data Structures and Algorithms
- Logical thinking

# Tools Used: 
- Pycharm = This was used for writing and running code
- Github = This was used to manage and showcase projects 

# Problems Solved: 
- Reverse a String
- Factorial of a number
- Sum of the digits
- Counting even and odd numbers in a list
- Find largest and smallest number in a list
- Check if a word or Number is a Palindrome
- prime number check 

# Problem 1: Reverse a String
def reverse_string(name):
    return name[::-1]

print(reverse_string("Reading"))


# Problem 2: Factorial of a number
def factorial(num):
   factorial = 1
   for i in range(1, num+1):
       factorial *= i
   return factorial

print(factorial(5))


# Problem 3: Sum of the digits

number = input("Enter a number Please ? ")
digit_sum = 0

for digit in number:
    digit_sum += int(digit)

print("The sum of digit is: ", digit_sum)


# Problem 4: Counting even and odd numbers in a list

list1 = [12,34,50,25,18]

even_num = 0
odd_num = 0

for num in list1:
    if num % 2 == 0:
        even_num += 1

    else:
        odd_num += 1

print("The even numbers in list1 are: ", even_num)
print("The odd numbers in list1 are: ", odd_num)


# Problem 5: Find largest and smallest number in a list

myList = [2,6,9,10,15]

largest_num = myList[0]
smallest_num = myList[0]

for num in myList:
    if num > largest_num:
        largest_num = num
    else:
        smallest_num = num

print("The largest number in the list is:", largest_num)
print("The smallest number in the list is:", smallest_num)


# Problem 6: Check if a word or Number is a Palindrome

word = input("Enter a String ? ")

string = str(word)
reversed_word = string[::-1]

if string == reversed_word:
    print("The word is a palindrome")
else:
    print("The word is not a Palindrome")


# Problem 7: prime number check 

num = int(input("Enter a number"))

if num <= 1:
    print("The number is not prime")

else:
    for i in range(2, num):
        if num % i == 0:
            print("The number is not prime.")
            break
    else:
        print("The number is a Prime.")
        
# Project File 
- I have attached the full source code below: 
[DSA_problems.py](https://github.com/user-attachments/files/22322975/DSA_problems.py)

