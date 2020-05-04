# Mac

## Dependencias

Antes de instalar latino, vamos a instalar todos paquetes necesarios:

```text
sudo port selfupdate
sudo port install flex bison cmake gcc g++ clang readline
```

## INSTALAR

```text
cd ~

 git clone --recursive https://github.com/primitivorm/latino
 cd latino
 git submodule update --init --recursive
 cmake .
 make
 sudo make install
```

### Pre requisitos

| Nombre paquete | Versión |
| :--- | :--- |
| bison | 3.04 |
| flex | 2.5.39 |
| cmake | 3.3.1 |
| gcc | 4.9.3 |
| g++ | 4.9.3 |
| readline | 7.0-2 |

## Ayuda en nuestro foro

[http://lenguaje-latino.org/foro/mac/](http://lenguaje-latino.org/foro/mac/)

Cualquier aportación o sugerencia es bienvenida.

