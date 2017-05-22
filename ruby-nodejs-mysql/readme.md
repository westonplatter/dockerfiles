# dockerfiles - ruby, nodejs, and mysql header files for rails env

## Versions
- Ruby 2.3.1
- Node 4.x
- Lib MySQL Dev Headers (?)


## build

Command to build,

```sh
docker build -t westonplatter/ruby-nodejs-mysql:2.3.1 -f Dockerfile-ruby-2.3.1 .
```


## publish

Command to push image to docker hub,

```sh
docker push westonplatter/ruby-nodejs-mysql:2.3.1
```
