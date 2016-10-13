# Tipos de datos
Un dato es toda aquella información que se puede tratar en un programa informático.
Un dato dentro de un programa se caracteriza por llevar asociado un identificador, un tipo y un valor.

* **Identificador**: Nombre para referenciar al dato dentro del programa
*Tipo: el tipo de un dato determina el rango de valores que puede tomar el dato y su ocupación en memoria durante la ejecución del programa
*Valor: Sera un elemento determinado dentro del rango de valores permitidos por el tipo de dato definido.

Algunos ejemplos de datos son: la edad, el saldo de una cuenta bancaria, el nombre de una persona, la letra del piso de una dirección, etc.

Latino cuenta con los siguientes tipos de datos:
*Logico: Representa verdad o falsedad para expresiones logicas, existen las palabras reservadas `verdadero` y `falso` para representar valores booleanos.

*Cadena: Una cadena de caracteres es un número de caracteres consecutivos (incluso ninguno) encerrado entre unos delimitadores determinados, en el lenguaje Latino son las comillas dobles o simples, Por ejemplo:
  ```
    nombre = "Juan Perez" #con comillas dobles
    direccion = 'Av. Siempreviva N 200'  #con comillas simples
  ```
*Números: Se emplean para representar números, por ejemplo:
```
edad = 15
area = 12.354
```

*Listas: Son un conjunto de datos enlistados uno despues de otro separados por coma y encerrados entre corchetes [ y ], por ejemplo:
```
frutas = ["naranja", "melon", "sandia"]
calificaciones = [10, 9, 8, 5]
```

*diccionarios: Son un conjunto par de valores sepadados por dos puntos (:) que tiene una clave y un valor, las claves deben de ser tipo cadena, y son encerradas entre llaves { y }, los valores par van separados por coma (,) por ejemplo:
```
#en este ejemplo 1 es la clave y "uno" es el valor
numeros = { "1" : "uno", 
            "2" : "dos", 
            "3" : "tres" } 
#otro ejemplo, juan es la clave y 9.5 es el valor de su promedio final
promedios = {"juan" : 9.5, 
             "lola" : 8.3, 
             "victor" : 9.2, 
             "pedro" : 7.1 }
```


