# Básico

Algunas cosas básicas a tomar en cuenta para empezar a programar

## Extención es  .lat

La extención con que se trabaja es **.lat**, debes tener cuidado al crear tus documentos y verificar bien que llevan esta extención

![.lat](../.gitbook/assets/extencion.png)

## Mostrar algo en pantalla

```text
escribir("Hola Latinos")
```

> También puedes usar el imprimir\(\) que es lo mismo, usa el que más te guste

```text
imprimir("Hola latinos")
```

## Obtener un valor del usuario vía la consola

Si quieres interactuar con el usuario y pedirle que introduzca alguna información, puedes usar este formato para hacerlo

```text
leer()
```

Esto lee lo que el usuario escribe, y lo podrias asignar a una variable para poder trabajar con los valores recojidos.  
Ejemplo

```text
escribir("Cual es tu nombre?")
nombre = leer()
escribir("Hola " . nombre)
```

> El punto '.' lo usamos para concatenar \(para juntar\)

![Ejemplo1](../.gitbook/assets/ejemplo-1.png)

