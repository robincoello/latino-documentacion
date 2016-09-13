# mientras ( while)
Mientras una condición se cumpla, se ejecutara el código repetidas veces hasta que ya no se cumpla, suele estar siempre acompañado de un contador u otra forma para que la condición cambie sino tendriamos un código de ejecución infinita.

```
mientras (condicion)
  codigo a ejecutarse
fin  
```


### Escribe 5 veces la frase "Debo estudiar"
```
i = 0
mientras ( i < 5 )
  escribir("Debo estudiar")
  i = i + 1
fin
```


```
i = 0
mientras (i < 10)
    si (i == 5)
        imprimir("cinco")
    sino
        imprimir(i)
    fin
    i = i + 1
fin
```
