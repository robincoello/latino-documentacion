# MAC

## Dependencias

Antes de instalar latino, vamos a instalar todos paquetes necesarios:

```
sudo apt-get update
sudo apt-get install bison flex cmake gcc g++ libjansson-dev 
sudo apt-get install libcurl4-openssl-dev libhiredis-dev redis-server 
sudo apt-get install curl libgtk-3-dev libreadline-dev libpthread-stubs0-dev

```

## INSTALAR

```
git clone --recursive https://github.com/primitivorm/latino
 
cd latino
git submodule update --init --recursive
cmake .
make
sudo make install
```

### Desinstalar

Puedes ver un video de como proceder aca [https://youtu.be/Q5xGm\_Bp22k](https://youtu.be/Q5xGm_Bp22k)

Pirmero debes saber donde esta instalado

```
whereis latino
```

Te dará algo parecido a esto:

```
latino: /usr/local/bin/latino

```

Ahora que sabemos dónde está solamente lo borramos:

```
sudo rm /usr/local/bin/latino

```



