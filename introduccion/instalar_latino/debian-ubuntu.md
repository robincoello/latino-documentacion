Puedes ver un video de como proceder aca 

[https://youtu.be/Q5xGm\_Bp22k](https://youtu.be/Q5xGm_Bp22k)Para la versión "Colibri" ejecuta las siguientes linea en la Consola

Empezamos por actualizar e instalar algunas de las librerias que necesitamos:

```
sudo apt-get update && apt-get install bison flex cmake gcc g++ libjansson-dev 
sudo apt-get install libcurl4-openssl-dev libhiredis-dev redis-server curl libgtk-3-dev 
sudo apt-get install libreadline-dev libpthread-stubs0-dev
```

Ahora la instlación propiamente dicha:

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

Cambiamos el nombre de latino para colibri

```
 sudo mv /usr/bin/latino /usr/bin/colibri
```

Copiamos la carpeta que viene con los ejemplos en nuestro repertorio personal

```
sudo mv /usr/bin/latino /usr/bin/colibri
```

Borramos todo lo que cargamos

```
cd ~/colibri_ejemplos
sudo rm -r ~/colibri
```

ejecutamos el ejemplo para la bienvenida

```
colibri bienvenida.lat
```



