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
