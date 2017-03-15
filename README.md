# keras-tf-gpu
Docker image for keras using tensorflow-gpu based on ubuntu 16.04

It includes:

* cuda 8.0
* cudnn 5.0
* tensorflow 1.0
* keras 2.0


## Usage

`nvidia-docker run --rm -ti xoryouyou/keras-tf-gpu bash`

When using tensorboard just put it in the background for example:

`tensorboard --logdir=/tmp/logs &`
