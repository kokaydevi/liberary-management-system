import sqlite3

connection = sqlite3.connect("bank.db")

cursor = connection.cursor()

cursor.execute("""
CREATE TABLE IF NOT EXISTS accounts (
    account_no TEXT PRIMARY KEY,
    name TEXT,
    balance REAL
)
""")

connection.commit()
connection.close()

print("Database created successfully!")
