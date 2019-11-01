# my-dockers

*alpine_python.tar*  → Modified Alpine distribution docker image, includes Python3 already installed.

*alpine-persistence.tar*  → Modified Alpine distribution docker image, includes a persistent folder located at /persistence.

To use in GNS3, download to GNS3 VM and run:

```
docker load < alpine_python.tar
docker load < alpine-persistence.tar
```
