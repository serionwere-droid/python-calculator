# python-calculator
A simple calculator built with Python


num_1= float(input('enter number: '))
operator = input('enter operator: ')
num_2= float(input('enter number: '))

if operator == '+':
    print('results:',num_1+num_2)

elif operator =='-':
    print('results:',num_1-num_2)
elif operator == "*":
    print("Result:", num_1 * num_2)

elif operator == "/":
    if num_2 != 0:
        print("Result:", num_1 / num_2)
    else:
        print("Cannot divide by zero")
else:
    print('invalid operator')
