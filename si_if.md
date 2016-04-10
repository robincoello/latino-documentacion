
# si (if)

El si verifica si la condicion se cumple ejecuta el codigo

```
si( condicion )
  codigo a ejecutarse
fin
```




### valor lógico directo
```
si(verdadero)
    imprimir("es verdadero")
fin
```

### asignado a una variable
```
b = verdadero
si(b)
    imprimir("es verdad")
fin
```
### si-sino
```
b = falso
si(b)
    imprimir("verdad")
sino
    imprimir("falso")
fin
```
### si anidado
```
i = 10
si(i == 0)
    imprimir(0)
sino si(i > 0)
        imprimir(1)
    sino
        imprimir(-1)
    fin
fin
```

```
si(verdadero)
    imprimir("hola latino")
fin
```

```
g = verdadero
imprimir(g)
si(g)
    imprimir(verdadero)
    imprimir('a')
sino
    imprimir("error")
fin
```


