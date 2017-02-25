# Comandos Ejecutables de Windows {#c-resumen-de-comandos-de-windows}

A continuación encontrará un subconjunto de los comandos de Windows que se pueden ejecutar en la consola o intérprete de comandos del sistema operativo. Varios de estos comandos son utilizados en los archivos ejecutables \(archivos.bat\) de los ejemplos que se desarrollan a lo largo de este libro.

Para obtener la lista completa de los comandos válidos utilice el comando help y, para obtener mayor información de un comando en particular, utilice

```
help  
<comando>
```

---

**Comando:**

```
CD o CHDIR

```

Muestra el nombre del directorio actual o permite cambiar de directorio.

CD

Muestra el nombre del directorio actual.

CD

Cambia el directorio actual.

---

**Comando:**

```
 CLS

```

Limpia el contenido de la pantalla.

CLS

---

**Comando:**

```
 CMD

```

Inicia una nueva[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)del intérprete de comandos.

CMD

Inicia un nuevo intérprete.

CMD /C

Inicia un nuevo intérprete, ejecuta el comando y termina.

CMD /K

Inicia un nuevo intérprete, ejecuta el comando y permanece activo.

---

**Comando:**

```
 COPY

```

Copia un[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo) a un directorio de destino.

COPY

Copia el[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo)origen en el destino.puede ser el nombre de un directorio o de un[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo).

---

**Comando:**

```
 DATE

```

Muestra o cambia la fecha del sistema.

DATE /T

Muestra la fecha del sistema.

DATE

Muestra la fecha del sistema y permite cambiarla.

---

**Comando:**

```
 DEL o ERASE

```

Borra uno o más archivos.

DEL

Borra cada uno de los archivos especificados en la lista de nombres.

puede incluir nombres de directorios y comodines para borrar varios archivos.

---

**Comando:**

```
 DIR

```

Muestra el contenido \(archivos y subdirectorios\) de un directorio.

DIR

Muestra el contenido del directorio actual.

DIR

Muestra el contenido del directorio indicado.

---

**Comando:**

```
 ECHO

```

Muestra un mensaje y permite activar y desactivar la salida del mismo comando ECHO.

ECHO ON

Activa la salida de mensajes del comando.

ECHO OFF

Desactiva la salida de mensajes del comando.

ECHO

Muestra el mensaje en la consola.

---

**Comando:**

```
 EXIT

```

Termina el intérprete de comandos, o un programa de comandos \([archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo).bat\).

EXIT

Sale de la[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)del intérprete de comandos.

EXIT /B

Sale de un programa de comandos \([archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo).bat\) sin salir de la[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)del intérprete.

---

**Comando:**

```
 FIND

```

Busca una cadena de texto en uno o más archivos del sistema.

FIND ""

Busca la cadena dada en los archivos especificados por

.puede contener comodines para especificar más fácilmente los archivos y directorios en los que se quiere hacer la búsqueda.

---

**Comando:**

```
 HELP

```

Brinda la información de ayuda para los comandos de Windows.

HELP

Lista todos los comandos junto con una descripción abreviada.

HELP

Muestra la ayuda detallada de un comando en particular.

---

**Comando:**

```
 MD o MKDIR

```

Crea un directorio o una ruta de directorios.

MD

Crea el directorio o la ruta de directorios indicada en. Si para ello hace falta crear directorios intermedios, este comando se encargará de ello.

---

**Comando:**

```
 MORE

```

Muestra por partes en la pantalla el contenido de un[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo)o la salida de un comando.

MORE

Muestra los archivos incluidos en la lista haciendo una pausa cada vez que se llena la pantalla.

comando \| MORE

Muestra la salida del comando haciendo una pausa cada vez que se llena la pantalla.

---

**Comando:**

```
 MOVE

```

Mueve archivos y cambia el nombre de archivos y directorios.

MOVE

Cambia de nombre el[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo)o el directorio.

MOVE

Mueve el[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo)al destino indicado.

---

**Comando:**

```
 PATH

```

Muestra o establece la ruta de búsqueda de los archivos ejecutables.

PATH

Muestra la ruta de búsqueda de los archivos ejecutables.

PATH

Establece las rutas de búsqueda. Diferentes rutas pueden separarse con el carácter ‘;’. Puede utilizar la[variable](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#variable)%PATH% para agregar las nuevas rutas a las establecidas con anterioridad.

PATH ;

Borra todas las rutas de búsqueda establecidas.

---

**Comando:**

```
 PAUSE

```

Suspende la ejecución de un programa de comandos y espera que el usuario oprima una tecla para continuar.

PAUSE

Suspende el proceso actual del programa y presenta el mensaje "Presione una tecla para continuar...".

---

**Comando:**

```
 PROMPT

```

Cambia el símbolo del sistema que se muestra en el intérprete de comandos.

PROMPT

Cambia el símbolo del sistema al texto indicado. Existen códigos para incluir caracteres especiales.

---

**Comando:**

```
 RD o RMDIR

```

Elimina un directorio.

RD

Elimina el directorio si está vacío.

RD /S

Elimina el árbol de directorios cuya raíz es.

RD /S /Q

Elimina el árbol de directorios cuya raíz essin pedir confirmación.

---

**Comando:**

```
 REM

```

Inicia un comentario en los archivos de programas de comandos \(archivos .bat\).

REM

Introduce el comentario indicado.

---

**Comando:**

```
 REN o RENAME

```

Cambia el nombre de un[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo).

REN

Cambia el nombre del[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo).

---

**Comando:**

```
 SET

```

Muestra, cambia o elimina las variables de entorno del intérprete de comandos.

SET

Lista todas las variables del entorno y los valores que tienen asignados.

SET

Muestra el valor asignado a.

SET=

Establece la cadena dada como valor de la[variable](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#variable)indicada.

---

**Comando:**

```
 START

```

Inicia una nueva[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)del intérprete de comandos.

START

Abre una nueva[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)sin ejecutar ningún programa o comando.

START

Abre una nueva[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)y ejecuta el comando indicado.

START

Abre una nueva[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)y ejecuta el[archivo](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#archivo)ejecutable indicado.

---

**Comando:**

```
 TIME

```

Muestra o cambia la hora del sistema.

TIME /T

Muestra la hora del sistema.

TIME

Muestra la hora del sistema y permite cambiarla.

---

**Comando:**

```
 TITLE

```

Establece el título de la[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)del intérprete de comandos.

TITLE

Cambia el título de la[ventana](https://universidad-de-los-andes.gitbooks.io/fundamentos-de-programacion/content/GLOSSARY.html#ventana)al indicado.

---

**Comando:**

```
 TYPE

```

Muestra el contenido de uno o más archivos de texto.

TYPE

Muestra el contenido de los archivos incluidos en la lista.

---

**Comando:**

```
 VER

```

Muestra la versión del sistema operativo Windows.

VER

Muestra la versión de Windows.

---

**Comando:**

```
 XCOPY

```

Copia árboles de archivos y directorios.

XCOPY

Copia los archivos incluidos en el directorio de origen al directorio de destino.

XCOPY /S

Copia todo el contenido \(directorios y archivos\) del directorio de origen al directorio de destino.

