[//]: # (Image References)
[image_mnist]: ./misc/GAN_MNIST.png
[image_celeba]: ./misc/GAN_CELEBA.png

# Generative Adversarial Network (GAN) implemented in TensorFlow
GAN is created and explored on two data sets (MNIST and a celebrity photo data set) using TensorFlow.

## Examples
### Novel handwritten digits are produced after training on the MNIST data set.
![GAN generated handwritten digits][image_mnist]

### Novel images of faces are generated after training the GAN on a celebrity photo data set.
![GAN generated celebrity faces][image_celeba]

## Project Information
The included [`./dlnd_face_generation.ipynb`](https://github.com/JackBurdick/GAN_face_generation/blob/master/dlnd_face_generation.ipynb) provides a commented walk though of the network generation and evaluation.

#### References:
* [tensor flow documentation](https://www.tensorflow.org/)

Note: Project created by Udacity as part of  [DLND](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)