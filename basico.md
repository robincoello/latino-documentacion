# Básico
Algunas cosas básicas a tomar en cuenta para empezar a programar en Latino


### Extensión de latino .lat
La extensión de latino es **.lat**, debes tener cuidado al crear tus documentos y verificar bien que llevan esta extensión 

![.lat](extencion.png)

### Qué versión estas usando?
Te aconsejo que uses la última versión de "Latino" ya que en cada nueva se van corrijiendo errores que se reportan.



### Mostrar algo en pantalla

```
escribir("Hola Latinos")
```
> También puedes usar el imprimir() que es lo mismo, usa el que más te guste

```
imprimir("Hola latinos")
```


### Obtener un valor del usuario vía la consola
Si quieres interactuar con el usuario y pedirle que introduzca alguna información, puedes usar este formato para hacerlo 
```
leer()
```
Esto lee lo que el usuario escribe, y lo podrias asignar a una variable para poder trabajar con los valores recojidos.
Ejemplo

```
escribir("Cual es tu nombre?")
nombre = leer()
escribir("Hola " . nombre)
```
> El punto '.' lo usamos para contatenar (para juntar)

![Ejemplo1](ejemplo 1.png)