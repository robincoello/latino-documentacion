# si \(if\)

`si`es una instrucción que permite la ejecución del código, si la condición que está entre los paréntesis se cumple

> donde condición es una expresión lógica \(verdadero o falso\)

su sintaxis es la siguiente:

```
si( condicion )
  #codigo a ejecutarse
fin
```

### Ejemplo

```
si(clave == "Srdp#ds9*/")
  escribir("Clave correcta")
fin
```

Aquí estoy comparando la variable  `clave` y si es igual a `Srdp#ds9*/` escribo "clave correcta.

Para que funcione realmente debo pedir al usuario la clave y quedaria así:

```
clave = leer()
si(clave == "Srdp#ds9*/")
  escribir("Clave correcta")
fin
```

Otro ejemplo para saber si el número es positivo

```
# se ocupa la funcion "leer" para leer un valor del teclado
escribir("Introduce un número:")
numero = leer()
si( numero >= 0 )
	escribir('El numero es positivo')
fin
```

En la línea `si( numero >= 0 )` realizamos la comparación si esta nos da `verdadero` ejecutamos todas las lineas hasta llegar al 'fin', en este ejemplo, el código `escribir('El numero es positivo')` se ejecuta siempre y cuando el usuario escriba un numero mayor o igual a cero.

video en youtube: /watch?v=GoPpFjNJfVE

Lo interesante es que podemos combinar muchas maneras de comparar dentro del si, ejemplo:

### Valor lógico directo

```
condicion = verdadero
si(condicion)
    escribir("Si, la comparación dio verdadero")
fin
```

Aqui la comparación se realiza con los valores lógicos buleanos 'verdadero \| falso '

### asignado a una variable

```
El valor buleano puede estar en una variable asi: 

b = verdadero
si(b)
    escribir("es verdad")
fin
```

Otros ejemplos

### Verifica si la clave es correcta

```
valor = '123'
si (valor) 
  escribir("La variable valor tiene un valor buleano positivo")
fin
```

> Ya que 0 es negativo y cualquier cosa diferente a cero es positivo



