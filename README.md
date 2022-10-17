# make-a-calculator in pthon 
#Show option to user
print("1. Addition (+)")
print("2. Subtraction (-)")
print("3. Multiplication (*)")
print("4. Division (/)")
userChoice = input("Enter your choice : ")
#take a decision
if userChoice=='+': #Addition
 #Read the values from user.
 n1 = int(input("Enter the number 1 : "))
 n2 = int(input("Enter the number 2 : "))
 #do the calculation
 res = n1 + n2;
 #display the result
 print("The Addition of " , n1 , " and " , n2 , " is ", res)
elif userChoice=='-': #subtraction
 #Read the values from user.
 n1 = int(input("Enter the number 1 : "))
 n2 = int(input("Enter the number 2 : "))
 #do the calculation
 res = n1 - n2
 #display the result
 print("The Subtraction of " , n1 , " and " , n2 , " is ", res)
elif userChoice=='*': #Multiplication
 #Read the values from user.
 n1 = int(input("Enter the number 1 : "))
 n2 = int(input("Enter the number 2 : "))
 #do the calculation
 res = n1 * n2;
 #display the result
 print("The Multiplication of " , n1 , " and " , n2 , " is ", res)
elif userChoice=='/': #Division
 #Read the values from user.
 n1 = int(input("Enter the number 1 : "))
 n2 = int(input("Enter the number 2 : "))
 #do the calculation
 res = n1 / n2;
 #display the result
 print("The Division of" , n1 , " and " , n2 , " is ", res)
else: #invalid
 print("you have entered invalid choice... try again.")
