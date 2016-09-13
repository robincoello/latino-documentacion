# hacer (do)
Ejecuta el código cuando la condicion se cumple, parecido al ```mientras``` pero en este nos aseguramos que el código se ejecute por lo menos una vez.

```
hacer
    código a ejecutarse   
cuando (condicion)
```



### Muestra del 0 al 9



```
i = 0
hacer
    imprimir(i)
    i++
cuando (i < 10)
```