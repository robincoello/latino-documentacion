# Funciones
Para crear una funcion debes usar el siguente formato

```
funcion nombre(argumentos)
  código interno a la funcion
fin
```
Para hacer el llamado a la funcion se usa el siguiente formato
```
nombre_funcion(argumentos)
```




### Función promedio

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
imprimir(promedio(3, 5)) #4
imprimir(max(3, 5)) #5
imprimir(min(3, 5)) #3
```