def account_report(name, account_no, balance):
    print("\n--- Account Report ---")
    print("Name:", name)
    print("Account Number:", account_no)
    print("Balance:", balance)


name = input("Enter name: ")
account_no = input("Enter account number: ")
balance = input("Enter balance: ")

account_report(name, account_no, balance)
