# Elegir

Si tenemos una compararación a ralizar con más de tres opciones posibles, esta es la mejor solución, se hace la comparación con cada caso posible, una vez encontrado simplemente ejecuta el código de ese caso y sale de `elegir`, si no encuentra ningun caso ejecuta lo que esta en por `defecto`

```
ciudad = 'Quito'

elegir(ciudad)
  caso 'Lima':
      escribir("Estas en Peru")
  caso 'Quito':
      escribir("Estas en Ecuador")      
  caso 'Cancun':
      escribir("Estas en Mexico")
  caso 'Caracas':
      escribir("Estas en Venezuela")
  caso 'Cali':
      escribir("Estas en Colombia")      
  defecto:
      escribir("No se donde estas")
fin
```

Ejecutando nos da

```
[robinson@fedora ejemplos]$ latino hola.lat 
Estas en Ecuador

```



