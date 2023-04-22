# Fedora ansible container

A container file to build an ansible enviroment for tests.
Just run:
```
# podman build -t ansible-test -f ContainerFile .
# podman run -it ansible-test bash
```
