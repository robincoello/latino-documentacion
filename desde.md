# desde

`Desde` permite dar un valor inicial a una variable, evaluar la condicion y dar un valor de incremento al valor inicial, y mientras la condición se cumpla, ejecutamos el código.

```
desde(valor_inicial, condicion, incremento)
  código a ejecutarse
fin
```

### Mostramos del 1 al 10

Este es un contador,`i=0`lo ponemos en cero, y mientras el contador sea inferior a 10, `i<10` a cada vuelta incrementamos el contador en uno `i++`.

```
desde(i=0; i<10; i++)
    escribir(i)
fin
```

Ejecutando nos da

```
[robinson@fedora ejemplos]$ latino hola.lat 
0
1
2
3
4
5
6
7
8
9

```



