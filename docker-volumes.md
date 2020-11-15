# Docker Volumes:
* Docker Containers are empheral (temporary) where as the data process by the containers should be persistent.
* Generally whenever a container is deleted the data in the container will also be lost.
* To preserve the data we can use docker volumes.

* A volume is an external device or an external directory which is mounted on a container in such a way that even
after the container is deleted the mounted volume data will be present.


## Docker uses 3 types of volumes
1. Simple Docker Volume
2. Sharable Docker Volumes
3. Docker Volume Container

1. Simple Docker Volume
- This is used for only preserving the data even though the container is deleted.
- This data will be available on the host machine but it cannot be used by other contianers

usecase:



