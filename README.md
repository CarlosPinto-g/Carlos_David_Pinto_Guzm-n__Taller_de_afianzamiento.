## Problemas_varios_1_pagina_N°2.

### (1) Desarrolla un programa que imprima el cuadrado de un número que el usuario ingresa mientras que el número ingrasado no sea negativo.
# código:
```python
numero = int(input("Ingresa un número: "))

while numero >= 0:
    cuadrado = numero ** 2
    print(f"El cuadrado de {numero} es {cuadrado}")
    numero = int(input("Ingresa otro número (negativo para salir): "))
```
# Imagen por pantalla
[![Captura-de-pantalla-40.png](https://i.postimg.cc/PxW4NQBW/Captura-de-pantalla-40.png)](https://postimg.cc/jwjNFPq2)


### (2) Desarrolla un programa que dado un n ́umero entero positivo n calcule e imprima (separados por espacios) n/2 si es par o 3n + 1 si es impar. El programa debe repetir el proceso con el n ́umero resultado de dicha operaci ́on mientras este sea diferente de 1. Por ejemplo para el n ́umero 3 debe imprimir 10 5 16 8 4 2 1.
# código:
```python
n = int(input("Ingresa un número entero positivo: "))

while n != 1:
    if n % 2 == 0:  
        n = n // 2
    else:         
        n = 3 * n + 1
```
# Imagen por pantalla 
[![Captura-de-pantalla-41.png](https://i.postimg.cc/TPXQxss3/Captura-de-pantalla-41.png)](https://postimg.cc/PC21zShg)


## Problemas_varios_2_pagina_N°3.

### (5) Diseñar una función que permita calcular el épsilon de la máquina.
# código:
```python
def calcular_epsilon():
    epsilon = 1.0

    while (1.0 + epsilon) != 1.0:
        epsilon = epsilon / 2.0
    epsilon = epsilon * 2.0
```
# Imagen por pantalla 
[![Captura-de-pantalla-43.png](https://i.postimg.cc/W10C00Lw/Captura-de-pantalla-43.png)](https://postimg.cc/xXT62JdX)


## Problemas_varios_1_paginan_N°5.

### (1) Imprimir un listado de los números del 1 al 100 cada uno con su respectivo cuadrado.
# código:
```python
for i in range(1, 101):
 print(i, i**2)
```
# Imagen por pantalla
[![Captura-de-pantalla-44.png](https://i.postimg.cc/YSDSB5nB/Captura-de-pantalla-44.png)](https://postimg.cc/p98vD6Ms)



### (2) Imprimir un listado con los números imparaes desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.
# código:
```python
print("Números impares del 1 al 999:")
for i in range(1, 1000, 2):
    print(i)

print("\nNúmeros pares del 2 al 1000:")
for i in range(2, 1001, 2):
```

# Imagenes por pantalla 1 hasta 999
[![Captura-de-pantalla-45.png](https://i.postimg.cc/SRSkPq8t/Captura-de-pantalla-45.png)](https://postimg.cc/XGzRZRsw)

# Imagen por pantalla 2 hasta 1000
[![Captura-de-pantalla-46.png](https://i.postimg.cc/nLqxcMGP/Captura-de-pantalla-46.png)](https://postimg.cc/QBNwf8PQ)


### (3) Imprimir los n ́umeros pares en forma descendente hasta 2 que son menores o iguales a un n ́umero natural n ≥ 2 dado.
# código:
```python
n = int(input("Ingresa un número natural (n ≥ 2): "))

print(f"Números pares desde {n} hasta 2 en forma descendente:")

for i in range(n, 1, -1):
    if i % 2 == 0:
```

# Imagen por pantalla 
[![Captura-de-pantalla-47.png](https://i.postimg.cc/GpKMQCL8/Captura-de-pantalla-47.png)](https://postimg.cc/GBBJL6sd)

### (4) Imprimir números de 1 hasta un número natural  n dado, cada uno con su respectivo factorial.
# código: 
```python
n = int(input("Ingresa un número natural: "))

factorial = 1
for i in range(1, n + 1):
    factorial *= i
    print(i, factorial)
```
# Imagen por pantalla
[![Captura-de-pantalla-48.png](https://i.postimg.cc/HxGQXv5n/Captura-de-pantalla-48.png)](https://postimg.cc/gwDXPDgb)




