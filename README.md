# Cats-and-Dogs-Dataset-with-Keras

  The Original Cats vs Dogs Dataset consists of 25,000 training images. I've selected only **2,000 images** for training set, **1,000 images** for validation set and further **1,000 images** for test set. Given a random image, we have to identify it as a cat or a dog. This shortened dataset in stored on Google Drive and each file contains code on how to access the dataset on Drive.
  
  I've implemented 3 different neural networks. The first one (Cats_Dogs_7449.ipynb) consists of bunch of Convolution and Pooling layers, all trained from scratch. This gives **74.49% accuracy** on 30 epochs. The second implementation (Cats_Dogs_7725.ipynb) makes the use of ImageDataGenerator along with a model similar to that of the first example. This gives **77.25% accuracy** after training for 50 epochs. The third model (Cats_Dogs_9439.ipynb) uses a pre-trained VGG16 model, initially with a self-trained classifier, and again with fine tuning of the fifth convolutional block and the self-trained classifier. This gives **94.39% accuracy** on 30 epochs.
  
  Thus, the various techniques of applying Convolution Neural Networks in Image Classification are shown, and the results clearly indicate which methods are superior in terms of accuracy.
  
  All implementations are made using **Keras**. This example was inspired by the book **Deep Learning with Python** written by Keras author Francois Chollet. 
  
  The files are created in Google Colab. Link is included.
  
  Comments and Suggestions are welcome :)
  
  Author: Raahat Gupta
  Date: 28/08/2018
