## Problemas_varios_1_pagina_N°2

### (1) Desarrolla un programa que imprima el cuadrado de un número que el usuario ingresa mientras que el número ingrasado no sea negativo.
# codigo:
```python
numero = int(input("Ingresa un número: "))

while numero >= 0:
    cuadrado = numero ** 2
    print(f"El cuadrado de {numero} es {cuadrado}")
    numero = int(input("Ingresa otro número (negativo para salir): "))
```
# Imagen por pantalla
[![Captura-de-pantalla-40.png](https://i.postimg.cc/PxW4NQBW/Captura-de-pantalla-40.png)](https://postimg.cc/jwjNFPq2)


### (2) Desarrolla un programa que dado un n ́umero entero positivo n calcule e imprima (separados por espacios) n/2 si es par o 3n + 1 si es impar. El programa debe repetir el proceso con
el n ́umero resultado de dicha operaci ́on mientras este sea diferente de 1. Por ejemplo para el n ́umero 3 debe imprimir 10 5 16 8 4 2 1.

