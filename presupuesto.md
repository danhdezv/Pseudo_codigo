# Calcular cuanto dinero me presta un amigo

## Problemática

Queremos pedir prestado a un amigo, pero solo nos puede prestar dinero con solo billetes de $100 infinitos. 

Diseñar un programa que debe indicarnos cuantos billetes de $100 me puede prestar y cuanto dinero no podra  

prestarnos por que no tiene monedas ni billetes para cubrir la cantidad.

## Pseudocodigo 

Inicio
    leer cantidad_prestamo

    imprimir "billetes de 100 que me puede prestar " cantidad_prestamo / 100 
    imprimir "dinero que no prestara " cantidad_prestamo % 100


fin

## Corrida de prueba 1
    cantidad_prestamo = 100
    "billetes de 100 que me puede prestar "   100 / 100 = 1
    "dinero que no prestara " 100 % 100 = 0  


## Corrida de prueba 2
cantidad_prestamo = 1234
    "billetes de 100 que me puede prestar " 1234 / 100 = 12
    "dinero que no prestara " 1234 % 100 = 34  

## Corrida de prueba 3
cantidad_prestamo = 10
    "billetes de 100 que me puede prestar " 10 / 100 = 1
     "dinero que no prestara " 10 % 100 = 10  

