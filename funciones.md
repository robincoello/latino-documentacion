# Funciones
Una función nos permite crear un pedazo de código el cual podemos ejecutarlo en otra parte tantas veces lo deseamos.

Para crear una funcion debes usar el siguente formato
> En esta versión, latino no acepta argumentos opcionales

```
funcion nombre(argumentos)
  código interno a la funcion
fin
```

Para hacer el llamado a la funcion se usa el siguiente formato

```
// llamamos la funcion
nombre_funcion(argumentos)
```

### Ejemplo de funciones

```
funcion promedio(a,b)
    retorno (a+b)/2
fin
```

```
funcion max(a,b)
    si (a > b)
        retorno a
    sino
        retorno b
    fin
fin
```

```
funcion min(a,b)
    si (a < b)
        retorno a
    sino
        retorno b
    fin
fin
```


### Llamado de las funciones anteriores
```
escribir(promedio(3, 5)) #4
escribir(max(3, 5)) #5
escribir(min(3, 5)) #3
```