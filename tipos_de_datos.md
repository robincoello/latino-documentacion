# Tipos de datos

Un dato es toda aquella información que se puede tratar en un programa informático.  
Un dato dentro de un programa se caracteriza por llevar asociado un identificador, un tipo y un valor.

* **Identificador**: Nombre para referenciar al dato dentro del programa.
* **Tipo** : El tipo de un dato determina el rango de valores que puede tomar el dato y su ocupación en memoria durante la ejecución del programa.
  \*Valor: Será un elemento determinado dentro del rango de valores permitidos por el tipo de dato definido.

Algunos ejemplos de datos son: la edad, el saldo de una cuenta bancaria, el nombre de una persona, la letra del piso de una dirección, etc.

### Latino cuenta con los siguientes tipos de datos:

* **Lógico**: Representa verdadero o falso para expresiones lógicas, existen las palabras reservadas `verdadero` y `falso` para representar valores booleanos, un valor falso es el cero, y todo otro valor sea cual sea es verdadero

* **Cadena**: Una cadena es un grupo de caracteres \(letras, números u otro caracter\), se debe representar entre comillas simples o dobles

  ```
  nombre = "Juan Perez" 
  direccion = 'Av. Siempreviva N 200'
  ```

* **Números**: Se emplean para representar números, por ejemplo:

  ```
  edad = 15
  area = 12.354
  ```

> Los números no se debe poner ni comillas simples ni dobles ya que si lo haces se consideraría como una cadena

* **Listas**: Son un conjunto de datos enlistados uno despues de otro, separados por coma y encerrados entre corchetes \[ y \], por ejemplo:

  ```
  frutas = ["naranja", "melon", "sandia"]
  calificaciones = [10, 9, 8, 5]
  ```

* **Diccionarios**: Son un conjunto par de valores sepadados por dos puntos \(:\) que tiene una clave y un valor, las claves deben de ser tipo cadena, y son encerradas entre llaves { y }, los valores par van separados por coma \(,\) por ejemplo:

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



