# Code-0
Project 0

#Simple program to tell the month with inserted value
month_list = ['January', 'Feburary', 'March', 'April', 'May', 'June', 'July', 
              'August', 'September', 'October', 'November', 'December']
try:
    month = int(input('Enter the Number of the Month : '))
    if month < 1 or month > 12:
        raise ValueError
    else:
        print(month_list[month - 1])
except ValueError:
    print("That's not a Month!")
