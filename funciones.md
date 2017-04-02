# Funciones

Una función nos permite crear un pedazo de código el cual podemos ejecutarlo en otra parte tantas veces lo deseamos.  
Una lista de las funciones esta disponible aca [http://lenguaje-latino.org/doc/](http://lenguaje-latino.org/doc/)

Para crear una función debes usar el siguiente formato:

```
funcion nombre(argumentos)
  código interno a la funcion
fin
```

> Por el momento \(versión 0.8.11\), latino no acepta argumentos opcionales

Para hacer el llamado a la función se usa el siguiente formato

```
nombre_funcion(argumentos)
```

### Ejemplo

Vamos a crear tres funciones: promedio, max, min

```
// me calcula el promedio de dos valores dados

funcion promedio(a,b)
    retorno (a+b)/2
fin
```

```
// paso dos valores y me da el valor más alto

funcion max(a,b)
    si (a > b)
        retorno a
    sino
        retorno b
    fin
fin
```

```
// paso dos valores y me da el más chico

funcion min(a,b)
    si (a < b)
        retorno a
    sino
        retorno b
    fin
fin
```

### Llamado de las funciones anteriores

Y ahora para poder ejecutar o hacer el llamado de las funciones debemos hacerlo así:

```
escribir(promedio(3, 5)) #4
escribir(max(3, 5)) #5
escribir(min(3, 5)) #3
```



