# Deep Learning - Face Generation project

This is a generative adversarial network (GAN) that generates images of faces. To ensure the network was training correctly is was initially trained on
the [MNIST](http://yann.lecun.com/exdb/mnist/) which contains images of handwritten digits. This allowed it to generate images of digits. Next it was trained on
the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) which contains over 200,000 images of celebrities. This allowed the model
to generate new images of faces.

This project is using Python 3 and needs the following libraries:

* numpy
* tqdm
* PIL
* tensorflow
* matplotlib
* jupyter notebook

These can be installed using pip or conda if using [Anaconda](https://www.continuum.io/downloads).

The project is implemented in a Jupyter notebook and can be run using the following from a terminal:

```jupyter notebook dlnd_face_generation.ipynb```

<br/>
If interested in training your model on a GPU for better performance, checkout <a href="http://www.floydhub.com">FloydHub</a>.
