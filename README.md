# dockerfiles
Just a hodgepodge of Dockerfile goodness

## generic

build (within image specific folder)
```sh
docker build -t westonplatter/ruby-nodejs-postgres:2.3.1 .
```

push to docker hub
```sh
docker push westonplatter/ruby-nodejs-postgres:2.3.1
```


## versioned

build (within image specific folder)
```sh
docker build -t westonplatter/ruby-nodejs-postgres:2.3.1 -f Dockerfile-ruby-2.3.1
```

pust to docker hub
```sh
docker push westonplatter/ruby-nodejs-postgres:2.3.1
```
