# python
Custompythonimage
A ready to use python interpreter on the go 

```````````````````````````````````````````````````````````````````````````````````````````````````````
How to Use:
$ docker build -t <custom-name for image> .
Once build check the image name by running $docker images
Run $docker run -it --name <randomNameForYourContainer> imageName:tag
  
For example:
$ docker build -t python:v3 .
$ docker images
REPOSITORY                     TAG                 IMAGE ID            CREATED             SIZE
python                         3                   3fedc8029dd7        5 minutes ago       301MB

$ docker run -it --name custompython python:v3
```````````````````````````````````````````````````````````````````````````````````````````````````````
