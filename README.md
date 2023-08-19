# ATM-Backend-interface
The primary objective of this project is to explore the functionality of an ATM machine and its impact on the user's account through transaction processing. The project involves studying the various operations and processes involved in ATM transactions, such as withdrawals, deposits, balance inquiries, and updating the user's account accordingly.

import datetime
e = datetime.datetime.now()


print(

     "                                                          Welcome To ATM"  )

print(
 "                                                        Please keep your card  "



    )

random_number=int(input(" please type any number if you  inserted your card in atm                "))
user_name='DHONI'
secrect_code=5858
account_balance=99000.0
user=(input("enter name"))
password=int(input("PLEASE ENTER THE PASSWORD         "))

if(user=='DHONI' and password==5858 ):
    print("        1) Deposit")
    print(          "        2) withdrawl")
    print(          "        3)mini statement")
    print("        4) exit")
    option=int(input("enter option"))
    if(option==1):
        deposit=float (input("enter deposit amount"))
        print( "total balance after deposition"     )
        account_balance=account_balance+deposit
        print(account_balance)
    elif(option==2):
        withdrawl=float(input("enter withdrawl amount"))
        print( "total balance after deposition"     )
        account_balance=account_balance-withdrawl
        print(account_balance)
    elif(option==3):
      
        print("================ ATM=====================")
        print ("Current date and time = %s" % e)
        print ("        Date:  = %s/%s/%s" % (e.day, e.month, e.year),"                Time : = %s:%s:%s" % (e.hour, e.minute, e.second))
        print ("                    ACCOUNT NUMBER= XXXXXXXXXXXX869             ")
        print ("Available account balance in your account is   =            ",account_balance)
        print ("                                      THANKYOU FOR VISITING                                     ")
    elif(option==4):
        print("you successfully exited")
        print(" Please visit again")
        print("Thank you")
    else:
        print(" You entered wrong option")
else:
    print(" User and password  entered is wrong Please take the card and enter correct password")



        
        
