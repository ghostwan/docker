# DockerFile to use libqi-python (qi)

This docker file facilitate the use of libqi-python.
It use the pip qi package : https://pypi.org/project/qi/1.6.7/#files of the opensource project https://github.com/aldebaran/libqi-python

## Build

> docker build . -t libqi-python:latest

## Run

To start the docker with the current folder mounted

> docker run --rm -it -v ${PWD}:/app libqi-python:latest

In the python editor, to load a script that was previously inside the mounted folder

> execfile('my_file.py')

