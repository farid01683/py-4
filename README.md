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
