# Variables

Una variable es una cadena \(conjunto de letras\) que toma un valor y este no cambia hasta que se le asigne otro valor, para definir una variable en "Latino" se hace de la siguiente manera:

## Variable de texto

El valor de una variable si contiene texto se debe encerrar en comillas simples `' '` o dobles. ```" "``.

```text
una_letra = 'a'
palabra = 'Latino'
frase = 'Latino, lenguaje de programación en español'
```

## Variable con valor númerico

```text
edad = 12
precio = 250.50
```

También se pueden encerrar entre comillas simples o dobles los valores númerios

```text
edad = '12'
precio = "250.50"
```

> Los decimales se separan por puntos

## Valor lógico o booleano

El valor booleano es algo que puede estar únicamente en dos estados: prendido o apagado, verdadero o falso, si o no, etc.

Aplicando esto a la programación en Latino existe el valor 0 "cero" para falso y cualquier otro: número, simbolo, letra o frase representa verdadero, incluso números negativos.

Para el tipo de dato cadena, la cadena vacia "", representa falso, cualquier otra cadena representa verdadero.

Para listas y diccionarios, cuando se encuentre vacio representará falso, mientras que si contiene al menos un elemento representará verdadero.

Existen las palabras reservadas `verdadero` y `falso` para representar este tipo de dato.  
Ejemplos:

```text
v = verdadero
f = falso

v = 1
f = 0

exito = 1
fracaso = 0

cad = ""
saludo = "hola"
lista_vacia = []

#se ocupa la funcion "lógico" para mostrar la representación del dato en booleano
escribir(logico(v))
escribir(logico(exito))
escribir(logico(f))
escribir(logico(fracaso))
escribir(logico(cad))
escribir(logico(saludo))
escribir(logico(lista_vacia))
```

> No olvidar que cero '0' es falso y cualquier cosa que sea diferente a cero es verdadero

