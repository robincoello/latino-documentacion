Para la versión "Colibri" ejecuta las siguientes linea en la Consola

Empezamos por actualizar e instalar algunas de las librerias que necesitamos:

```
sudo apt-get update && apt-get install git bison flex 
sudo apt-get cmake gcc g++ libjansson-dev libcurl4-openssl-dev 
sudo apt-get libhiredis-dev redis-server curl libgtk-3-dev 
sudo apt-get libreadline-dev libpthread-stubs0-dev
```

Ahora la instlación propiamente dicha:

```
 cd ~
 git clone https://github.com/robincoello/colibri
 cd colibri
 git submodule update –init –recursive
 cmake .
 make
 sudo make install
 sudo mv /usr/bin/latino /usr/bin/colibri
 mv ~/colibri/ejemplos ~/colibri_ejemplos
 cd ~/colibri_ejemplos
 sudo rm -r ~/colibri
 colibri bienvenida.lat
```

## Explicación:

Vamos al repertorio personal

```
 cd ~
```

Hacemos una copia de "Colibri"

```
 git clone https://github.com/robincoello/colibri
```

Ahora entramos en la caperta creada

```
cd colibri
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



