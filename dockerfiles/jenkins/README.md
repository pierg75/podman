# Fedora jenkins container

A container file to build a jenkins enviroment for tests.
Just run:
```
# podman build -t jenkins-test -f ContainerFile .
# podman run -p 8080:8080 jenkins-test
```
