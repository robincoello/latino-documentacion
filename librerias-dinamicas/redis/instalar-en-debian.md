# Instalar en Debian 9

Para instalar Redis en Debian

```text
sudo apt-get install redis-server
```

Una vez instalado lo lanzas con

```text
sudo systemctl start redis
```

Entras con tu navegador a

```text
http://127.0.0.1:6379
```

y te mostrara el siguiente mensaje

```text
-ERR wrong number of arguments for 'get' command
-ERR unknown command 'Host:'
-ERR unknown command 'User-Agent:'
-ERR unknown command 'Accept:'
-ERR unknown command 'Accept-Language:'
-ERR unknown command 'Accept-Encoding:'
-ERR unknown command 'Connection:'
-ERR unknown command 'Upgrade-Insecure-Requests:'
```

Esto nos indica que el Redis esta funcionando

Tambien puedes hacer lo siguiente

```text
ps aux | grep redis
```

y te mostrara algo parecido a esto:

```text
root@debian:/home/user# ps aux | grep redis
redis     2603  0.0  0.1  40860  2228 ?        Ssl  01:55   0:00 /usr/bin/redis-server 127.0.0.1:6379
root      2612  0.0  0.0  12784   952 pts/0    S+   01:55   0:00 grep redis
```

