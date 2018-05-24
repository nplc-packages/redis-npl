# redis-npl #

## About ##

A NPL/Lua client library for the Redis advanced key-value database,
which is based on [redis-lua](https://github.com/nrk/redis-lua) and NPL builtin sockets library.

## Install ##
```
nplc install nplc-packages/redis-npl
```

## Main features ##

- Support for Redis >= 1.2
- Command pipelining
- Redis transactions (MULTI/EXEC) with CAS
- User-definable commands
- UNIX domain sockets (when available in NPL builtin sockets library)


## Dependencies ##

- [NPLRuntime](https://github.com/LiXizhi/NPLRuntime)
- [NPLPackages](https://github.com/NPLPackages/main)


## Usages ##
Just see ./example or [redis-lua](https://github.com/nrk/redis-lua)
