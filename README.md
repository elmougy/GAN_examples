# GAN_examples

This project contains some examples on building GAN networks:

1- MNIST_GAN.ipynb: In this notebook, we'll be building a generative adversarial network (GAN) trained on the MNIST dataset to be able to generate new handwritten digits!

2- DCGAN_Example.ipynb: this notebook is an example of building a GAN using convolutional layers in the generator and discriminator.using <a href= "http://ufldl.stanford.edu/housenumbers/" >Street View House Numbers (SVHN) dataset.</a>

3- CycleGAN_Example.ipynb: this notebook is an example of a CycleGAN that reads in an image from a set  and transform it so that it looks as if it belongs in set . Specifically, using images of <a href = "https://en.wikipedia.org/wiki/Yosemite_National_Park">Yosemite national park </a> taken either during the summer of winter. The seasons are our two domains!

4- face_generation.ipynb: this project creates DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible! traininig using  <a href="http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html" >CelebFaces Attributes Dataset (CelebA)</a>



Environment: 
Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
pip install -r requirements.txt
