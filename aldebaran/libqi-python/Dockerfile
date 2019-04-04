FROM ubuntu:16.04
LABEL name=libqi-python version=0.0.1 maintainer=ghostwan@gmail.com

WORKDIR /app

RUN apt-get update \
    && apt-get upgrade -y \
    && apt-get install -y \
    python-pip

RUN pip install --no-cache-dir setuptools pip
RUN pip install --upgrade pip
RUN pip install --no-cache-dir wheel setuptools qi qicore qigeometry almath


ENTRYPOINT ["/usr/bin/python2.7"]

