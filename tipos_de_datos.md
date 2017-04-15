# Tipos de datos

* **Lógico**: Representa verdadero o falso para expresiones lógicas, existen las palabras reservadas `verdadero` y `falso` para representar valores booleanos, un valor falso es el cero, y todo otro valor sea cual sea es verdadero

```
// valores falsos
a = 0
a = falso

// valor verdadero
a = verdadero
a = 1
a = 'casa'
a = 900
```

* **Cadena**: Una cadena es un grupo de caracteres \(letras, números u otro caracter\), se debe representar entre comillas simples o dobles

  ```
  nombre = "Juan Perez" 
  direccion = 'Av. Siempreviva N 200'
  ```

* **Números**: Se emplean para representar números: enteros decimales, por ejemplo:

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



