# GCC with Nemu/C++ Docker Images

Configuration files for [Docker](https://www.docker.com/) images that contain [GCC](https://gcc.gnu.org/) and
the Nemu/C++ framework.

The images are available from [Docker Hub](https://hub.docker.com/r/nemuframework/gcc-nemu-cpp).

# Image Contents

The images are based on the [the official GCC Docker image](https://hub.docker.com/_/gcc) with the addition of
- the Nemu/C++ framework.

# Upload Instructions

```
docker build --no-cache .
docker tag <id> nemuframework/gcc-nemu-cpp:latest
docker tag <id> nemuframework/gcc-nemu-cpp:<version>
docker login
docker push nemuframework/gcc-nemu-cpp:latest
docker push nemuframework/gcc-nemu-cpp:<version>
```
