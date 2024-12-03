utthithi_bank = {}
account = 101
transaction = 'deposit'
cash = 10000
if transaction == 'deposit':
  if  utthithi_bank.get(account)==None:
    utthithi_bank[account]=cash
  else:
     utthithi_bank[account]+= cash
     #utthithi_bank.update({account:cash})
elif transaction=='withdraw':
   if utthithi_bank.get(account)==None:
      print("Invalid account number ", account)
   elif  cash <= utthithi_bank[account]:
       utthithi_bank[account]-=cash
       #utthithi_bank.update({account:cash})
   else:
      print(" Insufficient funds with your acc ", utthithi_bank[account])
elif transaction == 'balance':
     if utthithi_bank.get(account)==None:
        print("Invalid account number ", account)
     else:
        print("Balance cash ", utthithi_bank[account])
print(utthithi_bank)
