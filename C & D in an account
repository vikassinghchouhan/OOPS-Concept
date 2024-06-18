class Account:
    def __init__(self, bal, acc):
        self.balance = bal
        self.account_number = acc

    def credit(self, amount):
        self.balance += amount
        print("RS.", amount, "Was credited in account: ")
        print("Total Balance is: ", self.get_balance())

    def debit(self, amount):
        self.balance -= amount
        print("RS.", amount, "Was debited in account: ")
        print("Total Balance is: ", self.get_balance())
        
    def get_balance(self):
        return self.balance

acc1 = Account(1000, 123456)

acc1.credit(int(input("Enter the amount: ")))

acc1.debit(int(input("Enter the amount: ")))
