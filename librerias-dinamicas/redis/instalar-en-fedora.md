Para instalar redis en fedora 24

```
sudo dns install redis
```

Una vez instalado, lo lanzas con

```
redis-server
```

Y te dara algo asi:

    [robinson@fedora latino-redis]$ redis-server
    5673:C 26 Aug 01:37:14.005 # Warning: no config file specified, using the default config. In order to specify a config file use redis-server /path/to/redis.conf
    5673:M 26 Aug 01:37:14.006 # You requested maxclients of 10000 requiring at least 10032 max file descriptors.
    5673:M 26 Aug 01:37:14.006 # Server can't set maximum open files to 10032 because of OS error: Operation not permitted.
    5673:M 26 Aug 01:37:14.006 # Current maximum open files is 4096. maxclients has been reduced to 4064 to compensate for low ulimit. If you need higher maxclients increase 'ulimit -n'.
                    _._                                                  
               _.-``__ ''-._                                             
          _.-``    `.  `_.  ''-._           Redis 3.2.8 (00000000/0) 64 bit
      .-`` .-```.  ```\/    _.,_ ''-._                                   
     (    '      ,       .-`  | `,    )     Running in standalone mode
     |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
     |    `-._   `._    /     _.-'    |     PID: 5673
      `-._    `-._  `-./  _.-'    _.-'                                   
     |`-._`-._    `-.__.-'    _.-'_.-'|                                  
     |    `-._`-._        _.-'_.-'    |           http://redis.io        
      `-._    `-._`-.__.-'_.-'    _.-'                                   
     |`-._`-._    `-.__.-'    _.-'_.-'|                                  
     |    `-._`-._        _.-'_.-'    |                                  
      `-._    `-._`-.__.-'_.-'    _.-'                                   
          `-._    `-.__.-'    _.-'                                       
              `-._        _.-'                                           
                  `-.__.-'                                               

    5673:M 26 Aug 01:37:14.006 # WARNING: The TCP backlog setting of 511 cannot be enforced because /proc/sys/net/core/somaxconn is set to the lower value of 128.
    5673:M 26 Aug 01:37:14.006 # Server started, Redis version 3.2.8
    5673:M 26 Aug 01:37:14.006 # WARNING overcommit_memory is set to 0! Background save may fail under low memory condition. To fix this issue add 'vm.overcommit_memory = 1' to /etc/sysctl.conf and then reboot or run the command 'sysctl vm.overcommit_memory=1' for this to take effect.
    5673:M 26 Aug 01:37:14.007 # WARNING you have Transparent Huge Pages (THP) support enabled in your kernel. This will create latency and memory usage issues with Redis. To fix this issue run the command 'echo never > /sys/kernel/mm/transparent_hugepage/enabled' as root, and add it to your /etc/rc.local in order to retain the setting after a reboot. Redis must be restarted after THP is disabled.
    5673:M 26 Aug 01:37:14.007 * DB loaded from disk: 0.000 seconds
    5673:M 26 Aug 01:37:14.007 * The server is now ready to accept connections on port 6379

Esto muestra que el servidor de redis esta funcionando, ahora abre el navegador y entra a:

```
http://localhost:6379/
```

Si no te da error y vez lo siguiente, estas con redis funcionando

