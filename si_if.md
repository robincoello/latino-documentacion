# si (if)
'si',se usa para hacer una comparación si esta comparación es correcta se ejecuta el código que esta entre la palabra reserada 'si' y la palabra reservada 'fin', si la comparación es incorrecta el código simplemente es ingnorado. 

```
si( condicion )
  codigo a ejecutarse
fin
```
### Ejemplo
```
si( 10 > 0 )
 escribir('Si, es mayor') 
fin
```
Aquí tenemos tres lineas de código, en la primera ```si( 10 > 0 )``` realizamos la comparación si esta nos da correcto ejecutamos todas las lineas hasta llegar al 'fin', en este ejemplo 10 si es mayor a 0, asi que ejecutamos el código ```escribir('Si, es mayor')``` y en la tercer linea nos indica el final con la palabra 'fin'

Lo interesante es que podemos convinar muchas maneras de comparar dentro del si, ejemplo: 

### Valor lógico directo
```
si(verdadero)
    escribir("Si, la comparación dio verdadero")
fin
```
Aqui la comparación se realiza con los valores lógicos buleanos 'verdadero | falso '   


### asignado a una variable
```
El valor 
b = verdadero
si(b)
    escribir("es verdad")
fin
```

### Verifica si un número es positivo
```
numero = 15
si(numero >= 0 )
  escribir("El numero es potitivo")
fin  
```
{% youtube %}https://www.youtube.com/watch?v=GoPpFjNJfVE{% endyoutube %}

### Verifica si la clave es correcta
```
clave = 'robinson'
si (clave == '123abc') 
  escribir("La clave es correcta, puede entrar")
fin
```



