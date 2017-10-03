# Deep Learning From Scratch
## Introduction
I aim to reproduce some selected deep learning models from scratch as a kind of practice.

For obvious reason, I'm unable to train the model on ImageNet from scratch.

Therefore, all the models are trained on [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), whose images are rescaled to be as large as those described in the original papers.

If my model achieves comparable performance with the corresponding model given in the model zoo without pre-trained weight under the same setting in the first epoch, I consider it is a valid reproduction.

## Models
* [AlexNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)
* [VGG](https://arxiv.org/abs/1409.1556)
* [GoogLeNet](https://arxiv.org/abs/1409.4842)
* [ResNet](https://arxiv.org/abs/1512.03385)

## Model Zoo
My models are compared with models in this section.
* [AlexNet](http://pytorch.org/docs/master/torchvision/models.html#torchvision.models.alexnet)
* [VGG16](http://pytorch.org/docs/master/torchvision/models.html#torchvision.models.vgg16)
* [VGG19](http://pytorch.org/docs/master/torchvision/models.html#torchvision.models.vgg19)
* [GoogLeNet](https://github.com/apache/incubator-mxnet/blob/master/example/image-classification/symbols/googlenet.py)
* [ResNet34](http://pytorch.org/docs/master/torchvision/models.html#torchvision.models.resnet34)
* [ResNet50](http://pytorch.org/docs/master/torchvision/models.html#torchvision.models.resnet50)

