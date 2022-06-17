# Yaribed-Romero
#Listas, indicar el código

lista = ["1", "2", "3", "4"]
valor = input("ingrese un valor: ")

contador = 0
encontrado = False

for i in lista:
  if i == valor:
    print("su indice es", contador)
    contador += 1
    encontrado = True
    break
if encontrado == False:  
  print("el número no esta en la lista")
