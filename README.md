i = 1
while i < 5:
  i = i+ 1

  if i == 3:
    continue

  print(i)




****************
password =""

while password !="1234":
  password = input('enter your password:')

print('access granted')
*******



i = 1
while i <= 5:

  if i == 3:
    break

  print(i)
  i = i+ 1

*******password =""
attempt = 0
while password !="1234":
  password = input('enter your password:')
  attempt = attempt +1
  if attempt == 3:
    print('get out')
    break
if password == "1234":
  print('access granted')



  **********

  i = 1
while i <= 5:

  i = i+1

  print(i)





  ******

  for i in range(1,3):
  for j in range (i):
    print("*", end="" )
  print()  


for i in range(3):
  for j in range (4):
    print(i,j)


  for i in range(3,0, -1):
  for j in range (i):
    print("*", end="" )
  print()  



#choise = int(input('enter your choise(1-4):'))

choice == 1
secret = 7
guess= 0
print("welcome to guess the number(please guess between(1-10))")
while guess != secret :
  guess = int(input('enter your guess:'))
  if guess < secret:
    print('too low')
  elif guess > secret:
    print('too hige')  

  else:
    print('you won')  









    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

    mini game


    print("===========welcome to our small nintendo==========")
print("\n choose a game: ")
print("1. guess the number")
print("2. even odd checker")
print("3. multiplication checker")
print("4. exit")



choice = int(input("enter you choice(1-4):"))


choice == 1
secret = 7
guess= 0
print("welcome to guess the number(please guess between(1-10))")
while guess != secret :
  guess = int(input('enter your guess:'))
  if guess < secret:
    print('too low')
  elif guess > secret:
    print('too hige')

  else:
    print('you won')






  ###########################  mini game project 

while True:
  print("===========welcome to our small nintendo==========")
  print("\n choose a game: ")
  print("1. guess the number")
  print("2. even odd checker")
  print("3. multiplication checker")
  print("4. exit")



  choice = int(input("enter you choice(1-4):"))


  if choice == 1:
    secret = 7
    guess= 0
    print("welcome to guess the number(please guess between(1-10))")
    while guess != secret :
      guess = int(input('enter your guess:'))
      if guess < secret:
        print('too low')
      elif guess > secret:
        print('too hige')

      else:
        print('you won')



      #----------------------game 2-------------
  elif choice == 2:
    start = int(input("Enter The Number:"))
    end = int(input("Enter The End Number :"))

    print('Even Odd Check')

    for nub in range(start, end +1):
      if nub % 2 == 0:
        print(nub, "is even")
      else:
        print(nub, 'is odd')
#------------game 3-------------

  elif choice == 3:

    number = int(input("Enter The End Number :"))

    print(f'\n multipication table for {number}:')

    for i in range(1,11):
      result = number * i

      print(f'{number} * {i} = {result}')

#-------------4------

  elif choice == 4:
    print('thank you for playing')
    break


  else:
    print('envalid choice') 





***************************


a = int(input("enter: "))

if a % 2  == 0:
    print('even')
else:
    print('odd')





a = int(input())

for i in range(a + 1):
  if i % 2 == 0:
    print(i, end = " ")





    a = int(input())
i = 0
while i <= a:
  if i % 2 == 0:
    print(i, end = " ")
    i = i + 1



a = int(input())
i = 0

if a < 0:
  print('envalid')
else:

   while i <= a:
     if a % 2 == 0:

      print(i, end = " ")
     i = i + 2








##########################################

balance = 1000

while True:
    print("----- ATM MENU -----")
    print("1. Check Balance")
    print("2. Deposit Money")
    print("3. Withdraw Money")
    print("4. Exit")

    choice = int(input("Enter your choice: "))

    if choice == 1:
        print("Check Balance")
        print("Your current balance is:", balance)

    elif choice == 2:
        print("Deposit Money")
        amount = float(input("Enter deposit amount: "))
        balance = balance + amount
        print("Deposit successful")
        print("Updated balance:", balance)

    elif choice == 3:
        print("Withdraw Money")
        amount = float(input("Enter withdrawal amount: "))
        if amount <= balance:
            balance = balance - amount
            print("Please collect your cash")
            print("Updated balance:", balance)
        else:
            print("Insufficient balance")
            print("Current balance:", balance)

    elif choice == 4:
        print("Exit Program")
        print("Thank you for using the ATM")
        print("Have a nice day!")
        break

    else:
        print("Invalid choice. Please select between 1 and 4.")

    print()








    ################################


year = int(input("Enter a year: "))

if year <= 10:
    print("Invalid year. Please enter a valid year.")

elif (year % 4 == 0 and year % 100 != 0):
    print(year, "is a leap year.") 

elif (year % 100 == 0): 
    if (year % 400 == 0):
        print(year, "Century Leap Year.")
    else:
        print(year, "Century Year (Not Leap Year).")

else:
    print(year, "is not a leap year.")
    





###############################


import math

print("======welcome to smart billing system======")

running = True
total = 0.0
count = 0

while running:

 price = float(input("enter your price(0 to stop or exit): "))

 if price == 0:
     running = False

 elif price < 0 :
     print("price cannot be nagotable")
 else:
       total = total +  price
       count = count + 1

if  count == 0:
  print('no item purched')

else:
  print('total price', total)  

########### discount ###############
  if total >= 5000:
    discount = total * 0.20

  elif total >= 3000:
    discount = total * 0.10  

  else :
    discount = 0

  afer_discount = total - discount


##vat#############
  vat =  afer_discount * 0.05

  final_bill =  afer_discount  + vat

  final_bill = round(final_bill, 2)

  print('==========final_bill======')
  print('discount:',discount )
  print('vat:', vat)
  print('final_bill:', final_bill)

