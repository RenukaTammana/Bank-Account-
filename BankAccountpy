class BankAccount:
    def __init__(self, Acc_Holder = "", Acc_No = 0, Balance = 0):
        self.Acc_Holder = Acc_Holder
        self.Acc_No = Acc_No
        self.Balance = Balance

    def deposit( self, amt):
        if amt <= 0:
            print("Please enter positive amount to Deposit")
            return
        self.Balance += amt
        print(self.Balance , "is deposited to your Account . ")

    def withdraw(self,amt):
        if amt <= 0:
            print("Please enter positive amount to Withdraw")
            return
        if(amt > self.Balance ):
            print("Insufficient Funds .")
        else:
            self.Balance -= amt
            print(amt, " is withdrawn")

    def currentbalance(self):
        print("Your Account balance is ", self.Balance)


bankAcc = BankAccount("Alice" , 3133231 ,17350)

bankAcc.deposit(10000)

bankAcc.withdraw(5000)

bankAcc.currentbalance()

    
