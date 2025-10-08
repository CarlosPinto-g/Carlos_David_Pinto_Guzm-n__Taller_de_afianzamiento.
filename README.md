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

### (5) Diseñar una funci ́on que permita calcular el  ́epsilon de la m ́aquina.
