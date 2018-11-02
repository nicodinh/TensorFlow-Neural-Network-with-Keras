# TensorFlow-Neural-Network-with-Keras

## Tutorial - installation
- [Python3](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installing/)
- [Anaconda download](https://www.anaconda.com/download/#linux) - [Anaconda install](https://docs.anaconda.com/anaconda/install/) - [conda](https://conda.io/docs/user-guide/getting-started.html)
- [Keras](https://keras.io/#installation) using [Tensorflow](https://www.tensorflow.org/install/) for the back end
- [h5py](http://docs.h5py.org/en/latest/build.html)
- [Docker CE](https://docs.docker.com/install/)

```bash
conda create --name my-env
conda activate my-env
conda install tensorflow
conda install keras
mkdir ~/.keras
```
open .keras/keras.json
```json
{
    "image_data_format": "channels_last",
    "epsilon": 1e-07,
    "floatx": "float32",
    "backend": "tensorflow"
}
```
```bash
python3 create-neural-network.py
>>> Using TensorFlow backend.
```
