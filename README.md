
## Modification of floydhub/dl-docker
Forked from [floydhub](https://github.com/floydhub/dl-docker) and modified to support chainer.  Ubuntu image uipgraded to 16.04 for CPU version.

See the original [README.md](https://github.com/floydhub/dl-docker/blob/master/README.md).

## Specs
This is what you get out of the box when you create a container with the provided image/Dockerfile:
* Ubuntu 16.04
* [CUDA 8.0](https://developer.nvidia.com/cuda-toolkit) (GPU version only)
* [cuDNN v5](https://developer.nvidia.com/cudnn) (GPU version only)
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](http://keras.io/)
* [iPython/Jupyter Notebook](http://jupyter.org/) (including iTorch kernel)
* [Numpy](http://www.numpy.org/), [SciPy](https://www.scipy.org/), [Pandas](http://pandas.pydata.org/), [Scikit Learn](http://scikit-learn.org/), [Matplotlib](http://matplotlib.org/)
* [OpenCV](http://opencv.org/)
* [Chainer](http://chainer.org/)
* A few common libraries used for deep learning
