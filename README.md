# WSGN
When the paper is accepted, we will provide the corresponding dataset and code.

## 1. Preparing Dataset and Model
Datasets can be download from [data]() and take them into dir `data`.
## Requirements
The code implementation of **WSGN** mainly based on [PyTorch](https://pytorch.org/). All of our experiments run in Python 3.8.8.

## 2. Runing
Before running commands, you can set the hyperparameters in config.py. Please run the following commands and testing **WSGN** on different datasets: 
```
$ python ./run-cub.py       #CUB
$ python ./run-sun.py       #SUN
$ python ./run-awa2.py      #AWA2
```
**Note**: All of above results are run on a server with one GPU.
