# si sino \(if else\)

Esta es una extención del 'si', recordemos que con el 'si' si la condición no se cumple obviamos el código que está entre el 'si' y 'fin' pero en ocaciones necesitamos hacer algo si la condición no se cumple y así es para esto el 'sino'

Su extructura es la siguiente

```
si( condicion )
  codigo a ejecutarse SI se cumple la condición
sino
  código a ejecutarse cuando NO se cumple la condición
fin
```

Veamos un ejemplo

```
si( 10 > 0 )
 escribir("Si, es mayor a cero")
sino
 escribir("No, no es mayor a cero")
fin
```

En este caso en la primera línea del código hacemos la comparación, si esta es correcta ejecutamos lo que esta entre el 'si' y el 'sino' y si es incorrecta ejecutamos lo que está entre el 'sino' y 'fin'

### valor lógico directo

```
si(verdadero)
    escribir("es verdadero")
sino
    escribir("es falso")
fin
```

Como el valor booleano \(verdadero/falso\) falso es igual a cero '0' podriamos también hacer lo siguiente:

```
a = verdadero

si(a)
   poner("Es verdadero")
sino
   poner("Es falso")   
fin
```

### asignado a una variable

```
b = verdadero
si(b)
    escribir("es verdad")
sino
    escribir("es falso")
fin
```

### Verifica si un número es positivo

```
numero = 15
si(numero >= 0 )
  escribir("El numero es positivo")
sino
  escribir("El número es negativo ")  
fin
```

### Verifica si la clave es correcta

```
clave = 'robinson'
si (clave == '123abc') 
  escribir("La clave es correcta, puede entrar")
sino
  escribir("Clave incorrecta, intentelo nuevamente ")   
fin
```



