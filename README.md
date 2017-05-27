# A docker linux environment for C development

A linux environement for comfortable c development

https://hub.docker.com/r/nachinius/c-dev/

A friendly environment to develop in C.

- gcc, gdb, & colormake
- vim + exuberant-ctags
- bash-completion
- manpages-dev (colorized) for reference
- libc-dbg & locate to easily find the source code
- nodejs
- kernel-headers-generic

## use
### build
    docker build -t cdev .

### use
   docker run -it --rm -v "$PWD":/usr/src/app -w /usr/src/app cdev /bin/bash
