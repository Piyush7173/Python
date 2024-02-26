# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *
b) Print your name by using for loop

c) check the user name is palindrome or not
name = input("Enter your name: ")

Answer:-

print("a)")
print(" " * 3 + "*")
print(" " * 3 + "*      *")
print(" " * 3 + "*             *")
print(" " * 3 + "*              *")
print(" " * 3 + "*      *")
print(" " * 3 + "*")
print(" " * 3+ "*")
print(" " * 3 + "*")


print("b)")
for letter in name:
    print(letter, end=" ")
print()


palindrome = True
for i in range(len(name) // 2):
    if name[i] != name[-i - 1]:
        palindrome = False
        break

if palindrome:
    print("c) The name is a palindrome.")
else:
    print("c) The name is not a palindrome.")
