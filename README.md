# sync_server

Simple synchronous http server written with Boost.Beast

## Build

```shell
mkdir build && cd build
conan install .. -of .
cmake --preset conan-release ..
cmake --build .
```
