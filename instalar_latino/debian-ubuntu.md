# Debian / Ubuntu

Probado en:

* Debian 9

Empezamos por actualizar e instalar algunas de las librerias que necesitamos:

```text
sudo apt-get update 
sudo apt-get install git bison flex cmake gcc g++ 
sudo apt-get install libcurl4-openssl-dev libhiredis-dev libjansson-dev 
sudo apt-get install redis-server curl libgtk-3-dev 
sudo apt-get install libreadline-dev libpthread-stubs0-dev
```

Ahora la instalación propiamente dicha:

```text
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

```text
 cd ~
```

Hacemos una copia de "Latino"

```text
git clone --recursive https://github.com/primitivorm/latino
```

Ahora entramos en la caperta creada

```text
cd latino
```

Actualizamos las dependencias

```text
git submodule update –init –recursive
```

Copilamos e instalamos

```text
cmake .
make
sudo make install
```

Ejecutamos

```text
latino
```

y nos dara algo coo esto.

```text
Latino 1.0.0
Todos los derechos reservados (C) 2015-2017. Latinoamerica
latino>
```

Estamos listos para trabajar,

