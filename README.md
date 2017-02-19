# keras-tf-gpu
Docker image for keras using tensorflow-gpu

It includes:

* cuda 8.0
* tensorflow 1.0
* keras

## Usage

`nvidia-docker run --rm -ti xoryouyou/keras-tf-gpu bash`

When using tensorboard just put it in the background for example:

`tensorboard --log-dir=/tmp/logs &`
