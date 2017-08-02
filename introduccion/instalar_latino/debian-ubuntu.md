Empezamos por actualizar e instalar algunas de las librerias que necesitamos:

```
sudo apt-get update 
sudo apt-get apt-get install bison flex cmake gcc g++ 
sudo apt-get install libcurl4-openssl-dev libhiredis-dev libjansson-dev 
sudo apt-get install redis-server curl libgtk-3-dev 
sudo apt-get install libreadline-dev libpthread-stubs0-dev
```

Ahora la instalación propiamente dicha:

```
 cd ~
 git clone --recursive https://github.com/primitivorm/latino
 cd latino
 git submodule update --init --recursive
 cmake .
 make
 sudo make install
```

## Explicación:

Vamos al repertorio personal

```
 cd ~
```

Hacemos una copia de "Latino"

```
git clone --recursive https://github.com/primitivorm/latino
```

Ahora entramos en la caperta creada

```
cd latino
```

Actualizamos las dependencias

```
git submodule update –init –recursive
```

Copilamos  e instalamos

```
cmake .
make
sudo make install
```

Ejecutamos

```
latino
```

y nos dara algo coo esto.

```
Latino 0.9.1
Todos los derechos reservados (C) 2015-2017. Latinoamerica
latino>
```

Estamos listos para trabajar,

