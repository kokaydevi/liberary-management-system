balance = 0

deposit = float(input("Enter deposit amount: "))
balance += deposit

print("Current balance:", balance)

withdraw = float(input("Enter withdrawal amount: "))

if withdraw <= balance:
    balance -= withdraw
    print("Remaining balance:", balance)
else:
    print("Insufficient balance!")
