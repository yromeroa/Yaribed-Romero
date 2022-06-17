lista = ["1", "2", "3", "4"]
valor = input("ingrese un valor: ")

contador = 0
encontrado = False

for i in lista:
  contador += 1
  if i == valor:
    print("su indice es", contador)
    encontrado = True
    break
  
if encontrado == False:  
  print("el número no esta en la lista")
