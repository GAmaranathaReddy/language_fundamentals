# Online Python Compiler Example

Run the following Python 3 program to understand how `while` and `for` loops work with the `match` statement and conditional checks.

```python
# Online Python compiler (interpreter) to run Python online.
# Write Python 3 code in this online editor and run it.

day = 3
i = 1  # initial value 

while i <= 5:  # Loop condition 1<=5, 3<=5, 5<=5
    match day:
        case 1:
            print("Monday")
        case 2:
            print("Tuesday")
        case 3:
            print("Wednesday")
        case 4:
            print("Thursday")
        case 5:
            print("Friday")
        case _:
            print("Weekend")
    i += 1  # increment
    
    
# for (initial value; condition; increment)
# [1,2,3,4,5]  # Arrays
for j in range(1, 5, 2):
    print(j)
    day = 3
    match day:
        case 1:
            print("Monday")
        case 2:
            print("Tuesday")
        case 3:
            print("Wednesday")
        case 4:
            print("Thursday")
        case 5:
            print("Friday")
        case _:
            print("Weekend")
            
            
numbers = [1, 2, 3, 65, 78, 78, 67]
# Check every number and find even numbers
for number in numbers:
    print(number)
    if number % 2 == 0:
        print('Even')
    else:
        print('Odd')
