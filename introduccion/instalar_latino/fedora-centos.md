## Fedora

> Cada versión de fedora tiene una particularidad, por eso es mejor que cojas tu versión correcta, este procedimiento es porsi no esta en la lista tu versión

## Dependencias

Antes de instalar latino, vamos a instalar todos paquetes necesarios:

```
sudo dnf update
sudo dnf install bison flex cmake gcc g++ 
sudo dnf install libjansson-dev libcurl4-openssl-dev libhiredis-dev curl 
sudo dnf install redis-server jansson-devel 
sudo dnf install groupinstall "Development Tools" "Development Libraries" 
sudo dnf install groupinstall "RPM Development Tools" redhat-lsb libgtk-3-dev
```

## INSTALAR

```
cd ~
git clone --recursive https://github.com/primitivorm/latino
cd latino
git submodule update --init --recursive
cmake .
make
sudo make install
```

Ahora lo probamos

```
latino
```

Debe darnos esto

```
Latino 1.0.0
Todos los derechos reservados (C) 2015-2017. Latinoamerica
latino>
```

## Desinstalar

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

## Ayuda en nuestro foro

[http://lenguaje-latino.org/foro/fedora-centos/](http://lenguaje-latino.org/foro/fedora-centos/)

#### Cualquier aportación o sugerencia es bienvenida.



