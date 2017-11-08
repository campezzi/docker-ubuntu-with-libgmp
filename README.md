This is a _very_ simple Docker image containing only the latest LTS version of Ubuntu and the `libgmp10` package, intended to be used as a base image when running Haskell executables built with Stack, as described [here](https://docs.haskellstack.org/en/stable/GUIDE/#docker).

    docker pull campezzi/ubuntu-with-libgmp:latest
