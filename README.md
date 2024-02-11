# dwg2dxf

Here I just took one of the Dockerfiles from the original repo and made minor adjustments just to get the binaries out.

## Build & Run

```bash
docker build -t dwf2dxf-build . && \
docker run dwf2dxf-build
# etc... eg.
docker ps
docker exec -it CONTAINER_ID bash
zip stuff
docker cp CONTAINER_ID:/tmp/dwg2dxf.zip .
```
