import random

r=random.randrange(0,20)

pokusaj=0

while True :
   
  p=int(input('Unesite vaš broj: '))

  if r>p:
        print('Unijeli ste manji broj od našeg!')
        pokusaj=pokusaj+1
  if p>r:
        print('Unijeli ste veći broj od našeg!')
        pokusaj=pokusaj+1
  if p==r :
        print('Pogodili ste!')
        pokusaj=pokusaj+1
        break


print('Broj pokušaja: '+str(pokusaj))




