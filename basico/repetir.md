# repetir - hasta

Se parece a mientras pero en esta el codigo se ejecuta por lo menos la primera vez

```text
i= 0
repetir
    escribir(i)
    i++
hasta (i >= 5)
```

Ejecutando nos da:

```text
[robinson@localhost ejemplos]$ latino hola.lat 
0
1
2
3
4
```

Si ahora damos un valor inicial de 50

```text
i= 50
repetir
    escribir(i)
    i++
hasta (i >= 5)
```

Al ejecutar nos da

```text
[robinson@fedora ejemplos]$ latino hola.lat 
50
```

Esto es porque se ejecuta la primera vez donde i tiene el valor de 50 y al llegar a la comparacion i es superior o igual &gt;= a 5 asi que deja de repetir ya que esta es la condicion que pusimos.

Esta es una buena manera de asegurarnos que el codigo se ejecute por lo menos una primera vez

