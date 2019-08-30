
## seata-server

sh seata-server.sh -p 8091 -h 127.0.0.1 -m file

sh seata-server.sh(for linux and mac) or cmd seata-server.bat(for windows) [options]
  Options:
    --host, -h
      The host to bind.
      Default: 0.0.0.0
    --port, -p
      The port to listen.
      Default: 8091
    --storeMode, -m
      log store mode : file、db
      Default: file
    --help

## nacos 注册中心

https://github.com/alibaba/nacos

https://github.com/alibaba/nacos/releases/download/1.1.3/nacos-server-1.1.3.zip