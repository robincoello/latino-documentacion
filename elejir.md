# Elejir
Si tenemos una compararación a ralizar con más de tres opciones posibles, esta es la mejor solución, se hace la comparación con cada caso posible, una vez encontrado simplemente ejecuta el código de ese caso y sale de ```elejir ```

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