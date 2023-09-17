# Reto_4_Camilo_Sanchez

Adjunto tambien de forma de repositorio lo hecho

# Reto 4 - Cmailo Jose Sanchez Vilamar

Ejercicio #1: Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```pseudocode
x = int(input("ingrese un numero entero: "))

if x == 97 or x == 101 or x == 105 or x == 111 or x == 117:
  print( (x), " si es una vocal minuscula")
  print(chr(x))
else:
  print( (x), "no pertenece a una vocal minuscula")
```

Ejercicio #2: Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```pseudocode
x = input("ingrese una letra: ")
y = ord (x)

if y%2 == 0:
  print("el codigo de la letra si es par")
else: 
  print("el codigo de la letra no es par")
```

Ejercicio #3: Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```pseudocode
x = input("ingrese un caracter: ")

if x.isdigit():
  print("si es un digito")
else:
  print("no es un digito")
```

Ejecicio #4: Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

- Positivo: "El número x es positivo"
- Negativo: "El número x es negativo"
- Cero (0): "El número x es el neutro para la suma"

  
```pseudocode
x = float(input("ingrese un numero: "))

if x > 0:
  print("el numero",x,"es positivo")
  
elif x < 0:
  print("el numero",x,"es negativo")
  
elif x == 0:
  print("El número" ,x, "es el neutro para la suma")
```

Ejercicio #5: Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.


```pseudocode
x = float(input("ingrese la cordenada en x del centro del circulo: "))
y = float(input("ingrese la cordenada en y del centro del circulo: "))
r = float(input("ingrese el radio del circulo: "))

w = float(input("ingrese la coordena en x del punto: "))
z = float(input("ingrese la coordena en y del punto: "))

a = ((w - x) ** 2)
b = ((z - y) ** 2)
c = ((a + b) ** 0.5)

if c < r or c == r:
  print("la coordenada",w, "," ,z, "pertenece a la circunferencia")
else:
  print ("la coordenada no pertenece a la circuferencia")
```

Ejercicio #6: Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.


```pseudocode
x = float(input("ingrese la primera longitud: "))
y = float(input("ingrese la segunda longitud: "))
z = float(input("ingrese la tercera longitud: "))

if x + y > z and x + z > y and y + z > x: 
  print ("Se puede formar un triangulo con las longitudes")
else:
  print("No se puede formar un triangulo con las longitudes")
```

## Muchas gracias por leer el codigo :3
