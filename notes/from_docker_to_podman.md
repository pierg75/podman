# Just few notes to remember how to move fro docker to podman


1. Install podman:
```
# sudo dnf -y install podman podman-compose
```

2. Set an alias:
```
alias docker=podman
```

3. Make sure it works:
```
# docker run -rm hello-world
```

3b. Instead of doing this manually, you could instead install `podman-docker`
which does exactly this and more:
```
$ sudo dnf info podman-docker
Last metadata expiration check: 2:41:13 ago on Sun 16 Apr 2023 10:09:04 BST.
Available Packages
Name         : podman-docker
Epoch        : 5
Version      : 4.5.0
Release      : 1.fc37
Architecture : noarch
Size         : 82 k
Source       : podman-4.5.0-1.fc37.src.rpm
Repository   : updates-testing
Summary      : Emulate Docker CLI using podman
URL          : https://podman.io/
License      : Apache-2.0 and BSD-2-Clause and BSD-3-Clause and ISC and MIT and MPL-2.0
Description  : This package installs a script named docker that emulates the Docker CLI by
             : executes podman commands, it also creates links between all Docker CLI man
             : pages and podman.
```


