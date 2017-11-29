# MAC

## Dependencias

Antes de instalar latino, vamos a instalar todos paquetes necesarios:

```
sudo port selfupdate
sudo port install flex bison cmake gcc g++ clang readline
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

### 



