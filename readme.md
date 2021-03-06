## Resin + Movidius + Raspberry Pi 3

This project produces a base image for the [Movidius Neural Compute Stick](https://developer.movidius.com/). The image includes the [ncskd2](https://github.com/movidius/ncsdk), Tensorflow v1.7.0 and OpenCV 3.4.1.

This image does not build Caffe or the NCS Toolkit, so running/compiling the graphs in this image will fail, you should rather produce the graphs on an x86 Ubuntu machine as described in the NCS getting started.

For pre-built images grab them here: https://hub.docker.com/r/shaunmulligan/movidius-base/

Note to build this image you will need to either build on Docker for MacOS (which supports armv7 builds) or follow this blog post: https://resin.io/blog/building-arm-containers-on-any-x86-machine-even-dockerhub/


### List of Python modules installed:
absl-py (0.2.2)
astor (0.6.2)
bleach (1.5.0)
cycler (0.10.0)
Cython (0.28.3)
decorator (4.3.0)
enum34 (1.1.6)
gast (0.2.0)
graphviz (0.8.3)
grpcio (1.12.1)
h5py (2.7.0)
html5lib (0.9999999)
imutils (0.4.6)
lxml (3.7.1)
Markdown (2.6.8)
matplotlib (2.0.0)
mvnc (2.5.0.2)
networkx (2.1)
nose (1.3.7)
numpy (1.14.5)
opencv-contrib-python (3.4.1.15)
opencv-python (3.4.1.15)
picamera (1.13)
pip (9.0.1)
protobuf (3.6.0)
pygraphviz (1.3.1)
pyparsing (2.1.10)
python-dateutil (2.5.3)
pytz (2016.7)
PyYAML (3.12)
scikit-image (0.9.3)
scipy (0.18.1)
setuptools (33.1.1)
six (1.10.0)
tensorboard (1.7.0)
tensorflow (1.7.0)
termcolor (1.1.0)
Werkzeug (0.14.1)
wheel (0.31.1)
