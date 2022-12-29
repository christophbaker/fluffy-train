FROM conanio/gcc11:1.44.1

# switch to root
USER root

# install a few tools for more convenient developing
RUN  apt-get update; \
    apt-get -y install --fix-missing \
    cmake g++

USER conan
