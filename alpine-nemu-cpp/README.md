# Upload Instructions

```
docker build --no-cache .
docker tag <id> nemuframework/alpine-nemu-cpp:latest
docker tag <id> nemuframework/alpine-nemu-cpp:<version>
docker login
docker push nemuframework/alpine-nemu-cpp:latest
docker push nemuframework/alpine-nemu-cpp:<version>
```
