# Face Generator

Maybe you are designing a character and want to have its picture. Or maybe you are creating an online profile and just feel shy. Whatever your reason, you can use this generator to get an image of a realistic looking face.

For me, using deep learning to produce convincing, but artificial profile pictures is fun. And I am impressed with what this technology can do.

### Overview

I am using a GAN architecture and start with training a discriminator on a dataset of face images. Then I train the generator which will try to produce an image that is real to the discriminator, i.e. a face image.

### Methods

* GAN (Generative Adversarial Network)

### Tech

* Python
* PyTorch
* Matplotlib
* NumPy

### How to use

To take a look at the notebook, just click on `face_generator.ipynb` and it should open automatically.

You can also download the project and open the file `face_generator.html` in your browser to see the results.

## Dataset

I am training the model on [CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) which contains over 200,000 celebrity images.

I am using a subset of about 90,000 images. They were initially preprocessed by cropping out faces and resizing each of them to 64x64x3.

Here is a sample of this data.

<img src="images/preprocessed_face_data.png" width="500">
