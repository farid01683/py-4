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




