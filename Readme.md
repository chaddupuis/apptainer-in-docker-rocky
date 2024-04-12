# Apptainer within Docker / Rocky 8

A quick way to do apptainer image builds on machines without apptainer.  Generally for images used within HPC facilities, etc.

## Starting / Building
- to bring up a container you can work in:
```
docker compose -f docker-compose-tty.yml up
```
then you can use apptainer inside the container with:
```
docker exec -it apptainer-rocky-builder /bin/bash
```

- to just do a build:
(not finished yet...)
will use a build definition from xxx and build the image
```
docker compose -f docker-compose-builder.yml up
```


