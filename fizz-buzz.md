# Ejercicio Fizz-Buzz

## Consigna

Implementar un programa en Python que, para todos los numeros entre 1 y un numero n ingresado por el usuario (inclusive), imprima por pantalla el numero acompañado de: "Fizz" si el numero es divisible por 3; "Buzz" si es divisible por 5; "FizzBuzz" si el numero es divisible por 3 y 5 a la vez.

## Ejemplo

$n = 15$

Output:

```{python}
 1 
 2 
 3 Fizz
 4 
 5 Buzz
 6 Fizz
 7 
 8 
 9 Fizz
10 Buzz
11 
12 Fizz
13 
14 
15 FizzBuzz
```

## Bonus

a. Considerar como modificar la implementación si la consigna pide agregar el string "Cluf" si algun número es divisible por 7. Por ejemplo, para 21 se imprime FizzCluf, para 35 BuzzCluf, y para 105 FizzBuzzCluf. ¿Y si agrego otro caso más?

b. Implementarlo sin la estructura "if".

## Resolución

- Solución

```{python}
n : int = int(input("Ingrese su numero: "))

i : int
for i in range(1, n+1):
    if (i % 3 == 0) and (i % 5 == 0):
        print(i, 'FizzBuzz')
    elif (i % 3 == 0):
        print(i, 'Fizz')
    elif (i % 5 == 0):
        print(str(i) + ' Buzz')
    else:
        print(i)
```

- Solución Bonus a. (Más escalable)

```{python}
i : int
for i in range(1, n+1):
    output : str = str(i) + " "
    if (i % 3 == 0):
        output += "Fizz"
    if (i % 5 == 0):
        output += "Buzz"
    if (i % 7 == 0):
        output += "Cluf"
    
    print(output)
```

- Solución Bonus b.

```{python}
i : int
for i in range(1, n+1):
    output : str = str(i) + " "
    output += "Fizz" * (i % 3 == 0)
    output += "Buzz" * (i % 5 == 0)
    output += "Cluf" * (i % 7 == 0)
    print(output)
```
