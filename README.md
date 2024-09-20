# python-fundamentals
# Exercise 1: Print name, student number, and email
print("Bob")
print("ST1001")
print("bob@gmail.com")

# Exercise 2: Print name, student number, and email with escape sequences
print("Bob\nST1001\nbob@gmail.com")

# Exercise 3: Arithmetic operations with numbers 14 and 7
num1 = 14
num2 = 7
print(f"{num1} + {num2} = {num1 + num2}")
print(f"{num1} * {num2} = {num1 * num2}")
print(f"{num1} - {num2} = {num1 - num2}")
print(f"{num1} / {num2} = {num1 / num2}")

# Exercise 4: Display numbers 1 to 5 as steps
for i in range(1, 6):
    print(i)

# Exercise 5: Print a sentence with quotation marks and a line break
print("\"SDK\" stands for \"Software Development Kit\", whereas\n\"IDE\" stands for \"Integrated Development Environment\".")

# Exercise 6: Practice with escape sequences
print("python is an \"awesome\" language.")
print("python\n\t2023")
print('I\'m from Entri.\b')
print("\65")  # prints '5'
print("\x65")  # prints 'e'
print("Entri", "2023", sep="\n")
print("Entri", "2023", sep="\b")
print("Entri", "2023", sep="*", end="\b\b\b\b")

# Exercise 7: Define variables and perform type conversion
num = 23
textnum = "57"
decimal = 98.3
print(type(num))
print(type(textnum))
print(type(decimal))
sum_variables = num + int(textnum) + decimal
print(f"The sum is: {sum_variables}")
print(f"The type of the sum is: {type(sum_variables)}")

# Exercise 8: Calculate number of minutes in a year
days_in_year = 365
hours_in_day = 24
minutes_in_hour = 60
total_minutes = days_in_year * hours_in_day * minutes_in_hour
print(f"There are {total_minutes} minutes in a year.")

# Exercise 9: Ask user for name and greet
name = input("Please enter your name: ")
print(f"Hi {name}, welcome to Python programming :)")

# Exercise 10: Pounds to Dollars conversion
pounds = float(input("Please enter amount in pounds: £"))
conversion_rate = 1.39  # Example rate
dollars = pounds * conversion_rate
print(f"£{pounds} are ${dollars:.2f}")
