# Introduction

**¡Bienvenidos al manual de Latino!**

Éste es el manual para el Lenguaje de programación [Latino](http://lenguaje-latino.org/) el cual se caracteriza por tener una [sintaxis](https://es.wikipedia.org/wiki/Sintaxis) al Español. la versión en linea la encuentras en: [https://robincoello.gitbooks.io/latino/content/](https://robincoello.gitbooks.io/latino/content/) y en los servidores de latino aca [http://manual.lenguaje-latino.org/](http://manual.lenguaje-latino.org/)

## Como se crea esta documentación

Antes de seguir debes tener instalado:

```text
    git
    git ftp
    gitbook
```

Para generar, y publicar la documentación en [http://manual.lenguaje-latino.org/](http://manual.lenguaje-latino.org/) se realiza lo siguiente:

Primero creamos una carpeta en nuestra compu para alli trabajar, yo lo hare aca:

```text
/var/www/html/doc/doc_latino
```

Ahora clonamos el repertorio donde esta la documenación oficial de latino

```text
git clone https://github.com/robincoello/latino-documentacion.git
```

Esto nos pemitira tener la última versión del manual, ahora entramos en la carpeta que hemos clonado

```text
cd latino-documentacion
```

Solo una primera vez instalamos el pluging para youtube para gitbook

```text
gitbook install
```

Ahora seguimos

```text
#actualizamos
git pull
#generamos el _book
gitbook build
```

Ahora copiamos la carpeta \_book creada en otra parte para poder manipularla sola

```text
mkdir /var/www//html/doc/manual; 

cp -r _book/* /var/www/html/doc/manual
```

nos vamos a esta carpeta

```text
cd ../../manual/

Alli iniciamos in git

git init
```



Ahora configuramos el ftp del servidor de latino

```text
git config git-ftp.url "ftp.lengueje-latino.org" 
git config git-ftp.user "miusuario" 
git config git-ftp.password "misuperclave"
```

Verificamos haciendo un cat

```text
cat .git/config
```

nos debe dar algo parecido a esto

```text
[core] repositoryformatversion = 0 
filemode = true 
bare = false 
logallrefupdates = true 
[git-ftp] 
    url = ftp.lenguaje-latino.org 
    user = mans@lenguaje-latino.org 
    password = 2?A_0!XSfdeOiX5 

[pack] 
    buildbitmaps = false
```

ahora registramos las modificaciones antes de subir al servidor



```text
git add . 
git commit -m 'creacion de la doc'
```

con esto configurado, mandamos toros los archivos al servidor

```text
git ftp init
```

Listo, documentación creada y publicada en el servidor, si quieres ayudar en la redacción, corrección, de la documentación porfavor lee esto

chao

