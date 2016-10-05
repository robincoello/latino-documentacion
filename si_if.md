# si (if)
`si`: es una instrucción que permite la ejecución del código, si la condición que esta entre los parentesis se cumple, donde condicion es una expresion logica (verdadero o falso), su sintaxis es la siguiente:

```
si( condicion )
  #codigo a ejecutarse
fin
```
### Ejemplo

```
# se ocupa la funcion "leer" para leer un valor del teclado
escribir("Introduce un número:")
numero = leer()
si( numero >= 0 )
 escribir('El numero es positivo') 
fin
```
En la línea `si( numero >= 0 )` realizamos la comparación si esta nos da `verdadero` ejecutamos todas las lineas hasta llegar al 'fin', en este ejemplo, el código `escribir('El numero es positivo')` se ejecuta siempre y cuando el usuario escriba un numero mayor o igual a cero.

{% youtube %}https://www.youtube.com/watch?v=GoPpFjNJfVE{% endyoutube %}

Lo interesante es que podemos combinar muchas maneras de comparar dentro del si, ejemplo: 

### Valor lógico directo
```
condicion = verdadero
si(condicion)
    escribir("Si, la comparación dio verdadero")
fin
```
Aqui la comparación se realiza con los valores lógicos buleanos 'verdadero | falso '   


### asignado a una variable
```
El valor buleano se puede estar en una variable asi: 

b = verdadero
si(b)
    escribir("es verdad")
fin
```
Otros ejemplos

### Verifica si la clave es correcta
```
clave = 'robinson'
si (clave == '123abc') 
  escribir("La clave es correcta, puede entrar")
fin
```



