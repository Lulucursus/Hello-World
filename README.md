
L=[] #initialisation lite vide
n=int(input("Saisir un nombre entier"))
for k in range (1,n):
 if n%k==0:
  L.append(k)
print(L)
