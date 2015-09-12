# docker-ubuntu-java-python3
Base docker image based on Ubuntu, with Java 8 (openjdk) and Python 3 (with `pip` and `requests` modules preinstalled). It also includes supervisord for conveniently starting services within container.

## Usage
Get the image:
```
docker pull korekontrol/ubuntu-java-python3
```

Use it in `Dockerfile`:
```
FROM korekontrol/ubuntu-java-python3
```
