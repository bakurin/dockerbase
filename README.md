# Base docker images for different purposes

## 1. GO Build

The image has [dep](https://golang.github.io/dep) as dependency management and testing tools preinstalled. Might be used as build step in [multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build)