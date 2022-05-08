# Python_Calculator
x = int(input("Enter first number :"))
y = int(input("Enter second number :"))
print("Enter which operation would you like to perform")
op = input("Enter operator + , - , * , / :") 
if op =='+' :
    print(x, op , y ,'=',x+y)
elif op == '-' :
    print(x, op , y , '=',x-y)
elif op == '*' :
    print(x, op , y , '=',x*y)
elif op == '/' :
    print(x, op , y , '=',x/y)
else :
    print("Invalid Operator")
