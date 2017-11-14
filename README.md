# Basis-of-Feature-Spaces

This notebook is connected to a blog post that [explores the activation patterns](https://ptrrupprecht.wordpress.com/2017/11/14/the-basis-of-feature-spaces-in-deep-networks/) of neurons in a deep network (Inception, trained with ImageNet). It is based on Python/Tensorflow code available here.

As described in more detail in the blog, all of this was inspired by a publication by [Olah et al.](https://distill.pub/2017/feature-visualization/), Distill (2017).

The Jupyter Notebook is based on [an existing Python](https://github.com/tensorflow/models/blob/master/tutorials/image/imagenet/classify_image.py) script that is used to classify images based on the Inception network trained with the ImageNet dataset. The Jupyter Notebook extracts the activations of the Inception network when exposed to random input pictures (taken from Google Images; the pictures in the repository are not the same as the ones used for the data shown on the blog), and plots some statistical overviews of the activation patterns.
