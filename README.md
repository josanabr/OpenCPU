README.md
=========

This repository contains a Dockerfile used to deploy OpenCPU on an image. 

Build your image
----------------

In order to build your own image from the `Dockerfile` in this repository, execute

```
docker build -t opencpu .
```

Run your image
--------------

Once you have created your own image you can run a container from it as follows

```
docker run -it opencpu /bin/bash
```

Container executed
------------------

Once you are in the running container, you are running as `opencpu` user. User's password is `opencpu` and it is in the `sudo` group.

