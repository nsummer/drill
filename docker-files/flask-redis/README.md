<h1> Flask & Redis </h1>


# 1. Run command
- eg:
```shell
$ docker pull redis
$ docker run -d --name redis redis
$ docker build -t nancy/flask-redis .
$ docker run -d --link redis --name flask-redis -e REDIS_HOST=redis nancy/flask-redis
$ curl 127.0.0.1:5000
```