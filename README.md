# live-server-cs-sample
Testing repo for LiveServer VS Code extension

# pre-requisities
- mkcert https://github.com/FiloSottile/mkcert#installation
- docker-compose https://docs.docker.com/compose/install/

# setup

``` sh
mkcert -cert-file certificates/live-server.localhost.pem, -key-file certificates/live-server.localhost-key.pem
```

# run

``` sh
docker-compose up
```
