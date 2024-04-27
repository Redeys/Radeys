https://github.com/boto/botocore/blob/develop/botocore/data/location/2020-11-19/service-2.json#L90{"shape":"InternalServerException"},
        {"shape":"ResourceNotFoundException"},
        {"shape":"AccessDeniedException"},
        {"shape":"ValidationException"},
        {"shape":"ThrottlingException"}
      ],
      "documentation":"<p>Deletes a place index resource from your Amazon Web Services account.</p> <note> <p>This operation deletes the resource permanently.</p> </note>",
      "endpoint":{"hostPrefix":"cp.places.{"shape":"InternalServerException"},
        {"shape":"ResourceNotFoundException"},
        {"shape":"AccessDeniedException"},
        {"shape":"ValidationException"},
        {"shape":"ThrottlingException"}
      ],
      "documentation":"<p>Deletes a place index resource from your Amazon Web Services account.</p> <note> <p>This operation deletes the resource permanently.</p> </note>",
      "endpoint":{"hostPrefix":"cp.places.{"shape":"InternalServerException"},
        {"shape":"ResourceNotFoundException"},
        {"shape":"AccessDeniedException"},
        {"shape":"ValidationException"},
        {"shape":"ThrottlingException"}
      ],
      "documentation":"<p>Deletes a place index resource from your Amazon Web Services account.</p> <note> <p>This operation deletes the resource permanently.</p> </note>",
      "endpoint":{"hostPrefix":"cp.places.{"shape":"InternalServerException"},
        {"shape":"ResourceNotFoundException"},
        {"shape":"AccessDeniedException"},
        {"shape":"ValidationException"},
        {"shape":"ThrottlingException"}
      ],
      "documentation":"<p>Deletes a place index resource from your Amazon Web Services account.</p> <note> <p>This operation deletes the resource permanently.</p> </note>",
      "endpoint":{"hostPrefix":"cp.places.{"shape":"InternalServerException"},
        {"shape":"ResourceNotFoundException"},
        {"shape":"AccessDeniedException"},
        {"shape":"ValidationException"},
        {"shape":"ThrottlingException"}
      ],
      "documentation":"<p>Deletes a place index resource from your Amazon Web Services account.</p> <note> <p>This operation deletes the resource permanently.</p> </note>",
      "endpoint":{"hostPrefix":"cp.places.{"shape":"InternalServerException"},
        {"shape":"ResourceNotFoundException"},
        {"shape":"AccessDeniedException"},
        {"shape":"ValidationException"},
        {"shape":"ThrottlingException"}
      ],
      "documentation":"<p>Deletes a place index resource from your Amazon Web Services account.</p> <note> <p>This operation deletes the resource permanently.</p> </note>",
      "endpoint":{"hostPrefix":"cp.places.# Radeys
class Account:
    def __init__(self, name, balance=0):
        self.name = name
        self.balance = balance

    def deposit(self, amount):
        if amount > 0:
            self.balance += amount
            print(f"Deposited {amount} into {self.name}'s account.")
        else:
            print("Invalid deposit amount.")

    def withdraw(self, amount):
        if 0 < amount <= self.balance:
            self.balance -= amount
            print(f"Withdrew {amount} from {self.name}'s account.")
        else:
            print("Insufficient funds or invalid withdrawal amount.")

    def display_balance(self):
        print(f"Balance of {self.name}'s account: {self.balance}")


def main():
    print("Welcome to the Bank!")
    accounts = {}

    while True:
        print("\n1. Create Account\n2. Deposit\n3. Withdraw\n4. Display Balance\n5. Exit")
        choice = input("Enter your choice: ")

        if choice == "1":
            name = input("Enter account holder's name: ")
            accounts[name] = Account(name)
            print(f"Account for {name} created successfully.")
        elif choice == "2":
            name = input("Enter account holder's name: ")
            if name in accounts:
                amount = float(input("Enter amount to deposit: "))
                accounts[name].deposit(amount)
            else:
                print("Account not found.")
        elif choice == "3":
            name = input("Enter account holder's name: ")
            if name in accounts:
                amount = float(input("Enter amount to withdraw: "))
                accounts[name].withdraw(amount)
            else:
                print("Account not found.")
        elif choice == "4":
            name = input("Enter account holder's name: ")
            if name in accounts:
                accounts[name].display_balance()
            else:
                print("Account not found.")
        elif choice == "5":
            print("Thank you for using the Bank!")
            break
        else:
            print("Invalid choice. Please try again.")


if __name__ == "__main__":
    main()class Account:
    def __init__(self, name, balance=0):
        self.name = name
        self.balance = balance

    def deposit(self, amount):
        if amount > 0:
            self.balance += amount
            print(f"Deposited {amount} into {self.name}'s account.")
        else:
            print("Invalid deposit amount.")

    def withdraw(self, amount):
        if 0 < amount <= self.balance:
            self.balance -= amount
            print(f"Withdrew {amount} from {self.name}'s account.")
        else:
            print("Insufficient funds or invalid withdrawal amount.")

    def display_balance(self):
        print(f"Balance of {self.name}'s account: {self.balance}")


def main():
    print("Welcome to the Bank!")
    accounts = {}

    while True:
        print("\n1. Create Account\n2. Deposit\n3. Withdraw\n4. Display Balance\n5. Exit")
        choice = input("Enter your choice: ")

        if choice == "1":
            name = input("Enter account holder's name: ")
            accounts[name] = Account(name)
            print(f"Account for {name} created successfully.")
        elif choice == "2":
            name = input("Enter account holder's name: ")
            if name in accounts:
                amount = float(input("Enter amount to deposit: "))
                accounts[name].deposit(amount)
            else:
                print("Account not found.")
        elif choice == "3":
            name = input("Enter account holder's name: ")
            if name in accounts:
                amount = float(input("Enter amount to withdraw: "))
                accounts[name].withdraw(amount)
            else:
                print("Account not found.")
        elif choice == "4":
            name = input("Enter account holder's name: ")
            if name in accounts:
                accounts[name].display_balance()
            else:
                print("Account not found.")
        elif choice == "5":
            print("Thank you for using the Bank!")
            break
        else:
            print("Invalid choice. Please try again.")


if __name__ red=eys(code:'veper°{™not%ju}syw\\\\
account €}€gaminy '>not!atch
