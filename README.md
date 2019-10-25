# docker-cakephp2-template

By using Docker-Compose, you can build CakePHP2.10.19 and php5.5 environment easily.




### How to initialize

```
$ docker-compose build
$ docker-compose up -d
```

You can check at http://localhost:8000


### Mail config

```
-  'host' => 'localhost',
+  'host' => '<your mailhog container name>',
```

## Remove Containers

```
$ docker-compose down 
```


