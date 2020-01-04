# cs231n_DeepLearning280
Three homeworks of 280 course in ShanghaiTech University (2019-2020 winter).

# homework 1
PartA---about Mathamatics derivation and proof of Machine Learning
PartB---Softmax Classifier
        Perceptron Learning Algorithm
        Two-layer Neural Network

# homework 2
Fully-connected Neural Network
Batch Normalization
Dropout
Convolutional Neural Networks
Pytorch on CIFAR-10

# homework 3
RNN Captioning
LSTM Captioning
Network Visualization (Pytorch)
GANs (Pytorch)
Style Transfer (Pytorch)

# Some Notes

NOTE 1: The code has been tested to be compatible with python version 3.6 (it may work with other versions of 3.x). Python version can be confirmed by (1) activating virtualenv and (2) running which python.

NOTE 2: Please make sure that the version of packages installed are consistent with the requirements.txt. if the package is not installed, get it by pip install -r requirements.txt

NOTE 3: If you are working in a virtual environment on OSX, you may potentially encounter errors with matplotlib due to the issues described here. In our testing, it seems that this issue is no longer present with the most recent version of matplotlib, but if you do end up running into this issue you may have to use the start_ipython_osx.sh script from the partA-coding directory (instead of jupyter notebook above) to launch your IPython notebook server. Note that you may have to modify some variables within the script to match your version of python/installation directory. The script assumes that your virtual environment is named .env.
