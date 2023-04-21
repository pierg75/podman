# A simple dockerfile to run terraform in a container with podman

Build it:
```
# podman build . -t tf
```

Run it in a directory with a `main.tf` file:
```
# podman run --rm -it -v $PWD:/tf:Z tf init
```
