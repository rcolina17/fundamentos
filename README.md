# fundamentos

## Concatenación
Vimos tres formas para concatenar en python
    1. La primera fue utilizando el +, declaramos dos variables, la primera fue "name" que tenía almacenado Raul y la otra variable era edad que tenía almacenado 

        -Ejemplo: print(name +" tiene"+str(age)+" años")

    2. La segunda forma es utilizando llaves y .format()

        -Ejemplo: print("{} tiene {} años".format(name,age)) 
    
    3. La tercera fue utilizando string format

        -Ejemplo: print(f"{name} tiene {age} años")

## Funciones
En un archivo que lleva por nombre operations.py realizamos funciones con las operaciones básicas y también vimos como hacer una potencia.
    - Operaciones básicas: def sum(num1,num2):
                            return num1+num2
    
    - Potencia: 2**4=16

## Importaciones
Vimos como hacer importaciones de librerías. Hay varias maneras para importar las liberías.
    
    1. import operations
    print(operations.sum(10,5))

    2. from operations import sum
    
    3. from operations import *