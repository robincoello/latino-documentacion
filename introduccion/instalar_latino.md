# Instalar latino
Para cargar "Latino" deber ir al sitio oficial aca http://lenguaje-latino.org/descargar/

### Windows

* Carga el ejecutable en tu computadora y sigue los pasos 

### Linux

En vista de diferentes cambios que habido te recomiendo leas la forma de instalar aca http://lenguaje-latino.org/descargar que esta más actualizada.

~~Copia este código en una sola linea en la terminal 

```
sudo apt-get install git bison flex cmake gcc g++ libjansson-dev libcurl4-openssl-dev libhiredis-dev redis-server curl
 
 git clone --recursive https://github.com/primitivorm/latino
 cd latino
 git submodule update --init --recursive
 cmake .
 make
 sudo make install
```
~~



