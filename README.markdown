# redis-npl #

## About ##

A NPL/Lua client library based on [redis-lua](https://github.com/nrk/redis-lua) and NPL builtin sockets library.


## Main features ##

- Support for Redis >= 1.2
- Command pipelining
- Redis transactions (MULTI/EXEC) with CAS
- User-definable commands
- UNIX domain sockets (when available in NPL builtin sockets library)


## Dependencies ##

- [NPLRuntime](https://github.com/LiXizhi/NPLRuntime)
- [NPLPackages](https://github.com/NPLPackages/main)


## License ##

The code for redis-lua is distributed under the terms of the MIT/X11 license (see LICENSE).
