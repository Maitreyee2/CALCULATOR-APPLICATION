# CALCULATOR-APPLICATION
print ("***Mini Calculator ***")

num1 = float(input("Enter a number here: "))
num2 = float(input("Enter another number here: "))

print ("""
Press 1 For addition :
       
Press 2 For subtraction:

Press 3 For multiplication:

Press 4 For division""")

choice = int(input("Enter a number between 1-4: "))

if choice == 1:
    sum = num1+num2

    print ("The addition of the given two numbers is",sum)

elif choice == 2:
    print ("The subtraction of the given two numbers is",num1-num2)

elif choice == 3:
    print ("The multiplication of the given two numbers is",num1*num2)

elif choice == 4:
    print ("The division of the given two numbers is",num1/num2)

else:
    print ("Invalid Input from the User")
