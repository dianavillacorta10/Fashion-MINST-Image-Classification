# Fashion-MINST-Image-Classification

#1.What is the Fashion MNIST dataset?
   Is a publicly available image dataset used mainly for machine learning and deep learning, especially for image classification tasks.
   
#2.Why do we normalize image pixel values before training?
   We normalize image pixel values before training to make the learning process faster, more stable, and more accurate.Normalization makes training smoother,faster,and more reliable by      keeping pixel values within a manageable range.
   
#3.List the layers used in the neural network and their functions.
   1.Input layer – Accepts the 28×28 grayscale image (784 pixel values) as the model’s input.
   2.Flatten layer – Reshapes the 2D image into a 1D vector so it can be processed by fully connected layers.
   3.Dense (hidden) layer(s) with ReLU activation – Learns and extracts meaningful features by applying weighted transformations and   non-linear activation.
   4.Output Dense layer with Softmax activation – Converts the learned features into probability scores for the 10 Fashion MNIST classes.
   
#4.What does an epoch mean in model training?
   An epoch is one complete pass of the entire training dataset through the model, during which the model updates its weights based on the computed errors.
   
#5.Compare the predicted label and actual label for the first test image.
   The predicted label is what the model thinks the image is, and we check if it matches the actual label to see if it got it right.

#6.What could be done to improve the model’s accuracy?
   Focus on CNN architectures, proper preprocessing, regularization, and hyperparameter tuning — these give the biggest accuracy gains for image classification tasks like Fashion MNIST.

   .[This is the link of my Google Colab:](https://colab.research.google.com/drive/1rRBOz8_Yi0HHT7VLz9Bw3FHzFovkAC1O?usp=drive_link)
