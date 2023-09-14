# Repo_4_Camilo_Sanchez

Adjunto tambien de forma de repositorio lo hecho

# Reto 4 - Cmailo Jose Sanchez Vilamar

Ejercicio #1: Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

x = int(input("ingrese un numero entero: "))

if x == 97 or x == 101 or x == 105 or x == 111 or x == 117:
  print( (x), " si es una vocal minuscula")
  print(chr(x))
else:
  print( (x), "no pertenece a una vocal minuscula")
