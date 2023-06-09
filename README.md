# Intelligent Systems for Pattern Recognition
Solutions to the assignments from the Intelligent Systems for Pattern Recognition course \
Academic Year: 2022/23, University of Pisa

## Midterm 1: LoG Blob Detection (Assignment 6)
Implement the convolution of a Laplacian of a Gaussian blob (LoG) detector with an image and apply it to 3-4 images of your choice from the dataset (possibly from different thematic classes). Do not use library functions for implementing the convolution or to generate the LoG filter. Implement your own and show the code (the interesting bits at least)! The function you implement should be able to run the LoG for different choices of the scale parameter, which is passed as an input argument. Show the results of your code on the 3-4 example images, for different choices of the scale parameter (sigma).

[DATASET](http://download.microsoft.com/download/A/1/1/A116CD80-5B79-407E-B5CE-3D5C6ED8B0D5/msrc_objcategimagedatabase_v1.zip)


## Midterm 2: Restricted Boltzman Machine (Assignment 3)
Implement from scratch an RBM and apply it to DSET3. The RBM should be implemented fully by you (both CD-1 training and inference steps) but you are free to use library functions for the rest (e.g. image loading and management, etc.).

1. Train an RBM with a number of hidden neurons selected by you (single layer) on the MNIST data (use the training set split provided by the website).
2. Use the trained RBM to encode a selection of test images (e.g. using one per digit type) using the corresponding activation of the hidden neurons.
3. Reconstruct the original test images from their hidden encoding and confront the reconstructions with the original image (use a suitable quantitative metric to assess the reconstraction quality and also choose few examples to confront visually).

[DSET3 (Image processing: MNIST)](http://yann.lecun.com/exdb/mnist/)


## Midterm 3: Fake News Detection (Assignement 5)
The dataset contains real and fake news, including their title, text, subject, and date. The objective is to train a binary classifier to recognize fake news. You are free to choose the model's architecture, but you should describe and justify your design choices.

Notice that the fake and real news in the dataset are balanced. However, in the real world, real news are much more frequent than fake ones (hopefully). Simulate the effect of the data imbalance by undersampling/oversampling one of the classes in the training set and compute the test accuracy on a (balanced) test set. Then, try to use a mechanism to make the training robust to imbalances, such as weighting the loss for the samples depending on their class. Discuss the results of this mitigation.

NOTE ON PREPROCESSING: you are allowed to preprocess the data however you want (e.g. using pretrained embeddings, dropping some features, just a bag-of-words), but the classification model must be trained by yourself.

[DATASET (Fake News Classification)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)


## Midterm 4: Generative Adversarial Imitation Learning (Paper 9)
This midterm is based on reading and summarizing the main findings of a single paper chosen from the list provided below.

Students are expected to deliver a short presentation (no more than 8 slides) covering the following content:
1. Introduction to the problem
2. Model description
3. Key catch of the model, represented by a commented equation
4. Key (empirical) result
5. Comment on novelties, strong points and weaknesses

Paper: Ho and Ermon, Generative Adversarial Imitation Learning, NIPS 2016
