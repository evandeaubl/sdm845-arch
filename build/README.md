In order to build on an x86_64 machine, use `docker buildx`:

```
docker buildx build --platform arm64 -t $TAG --load .
```
