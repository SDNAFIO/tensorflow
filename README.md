## About
This repository is a fork from the official tensorflow repository.
Currently the following features have been added:

* Support for grouped convolutions using cuDNN
  - accessible through the `groups` parameter in `tf.layers.conv3d` and `tf.layers.conv2d`
  - Please note that grouped convolutions are only supported on GPUs at the moment, on CPUs an error will be thrown.
  
## Dependencies
The following environment has been used for testing:

* Cuda 10.0
* Cudnn 7.4.2
* Python 3.6
* Bazel 0.17.2
