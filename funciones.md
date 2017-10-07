# Funciones

Si quiero escribir mi dirección haria lo siguiente

```
escribir("Robinson Coello")
escribir("Lenguaje Latino")
escribir("Bruselas - Belgica")
escribir("Europa")
```

si ejecuto esto me daria esto:

```
[robin@localhost]$ latino demo.lat 
Robinson Coello
Lenguaje Latino
Bruselas - Belgica
Europa
```

Que pasaria si debo escribir mi dirección en 50 hojas de mi código, en realidad nada,  solo lo escribo 50 veces y listo, pero !!! y si me cambio de dirección, me tocaria buscar en las 50 hojas y correjir una a una las lineas las de mi dirección, esto no es nada practico, y para una `funcion` nos resuelve este problema

Primero creo una `funcion` con mi direción asi:

```
funcion direccion()
    escribir("Robinson Coello")
    escribir("Lenguaje Latino")
    escribir("Bruselas - Belgica")
    escribir("Europa")
fin
```

Una vez hecho esto, en cada lugar donde deseo que aparesca mi dirección solo hago el llamado a esa `funcion`

```
//...
direccion()
//...
```

De esta manera, tengo en un solo lugar los datos que contienen mi direción y si dese cambiarla lo hago en un solo lugar, a que nos facilita la vida?

quedando el codigo completo asi:

```
funcion direccion()
        escribir("Robinson Coello")
        escribir("Bruselas - Belgica")
        escribir("Europa")
fin

direccion()
```

## Avancemos más

Pero podemos ir mas lejos, si deseo escribir a mi novia en la misma dirección como hago? me tocaria escribir otra funcion con los datos de mi novia,

```
funcion direccion()
    escribir(" Patricia ")
    escribir("Lenguaje Latino")
    escribir("Bruselas - Belgica")
    escribir("Europa")
fin
```

Eso conlleva varias dificultadades y erroes de programación, no puedo tener dos funciones con el mismo nombre y no es optimo duplicar código así que lo mejor es hacer una sola `funcion` y pasarle el dato que cambia como parametro, en este caso el nombre

```
funcion direccion( nombre )
    escribir( nombre )
    escribir("Lenguaje Latino")
    escribir("Bruselas - Belgica")
    escribir("Europa")
fin
```

y le paso los nombres en el llamado

```
// para mi 
direccion(" Robinson Coello ")

// para mi nomvia
direccion(" Patricia ")
```

Asi solo uso una funcion

Ya se lo que estas pensando ;\) y si mi novia me deja y se cambia de casa? jjeee pues no le escribo! bueno supongamos que le quiero escribir lo mejor seria hacer modificaciones a esa funcion para que sea valido para cualquier direccion asi:

```
funcion direccion( nombre, empresa, ciudad, pais, continente )
    escribir( nombre )
    escribir( empresa )
    escribir( ciudad .. " " .. pais)
    escribir(continente)
fin
```

Y le paso los datos en el llamdo de la `funcion`

```
direccion("Robinson Coello","Lenguaje Latino","Bruselas","Bélgica","Europa")
```

Y para mi novia

```
direccion("Patricia Wilm","Lenguaje Latino","Cali","Colombia","Sur America")
```

Y nos dara como resultado

```
Robinson Coello
Lenguaje Latino
Bruselas Bélgica
Europa

Patricia Wilm
Lenguaje Latino
Cali Colombia
Sur America
```

Este es el codigo completo

```
funcion direccion( nombre, empresa, ciudad, pais, continente )
escribir( nombre )
escribir( empresa )
escribir( ciudad .. " " .. pais)
escribir(continente)
fin

direccion("Robinson Coello","Lenguaje Latino","Bruselas","Bélgica","Europa")

direccion("Patricia Wilm","Lenguaje Latino","Cali","Colombia","Sur America")
```

> Una funcion siempre debe estar antes del lugar de donde se hace el llamado

Y el orden de los parametros deben ser respetado

Y asi podemos definir tantas funciones como lo queramos, y cada una con una labor determinada, pero `latino` nos facilita la vida y ya los creadores han creado algunas funciones y a estas que viene instaladas en `latino` se les llama funciones nativas.

## Funciones nativas



































