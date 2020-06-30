# Pneumonia_detection

This is a comparison of different Convolutional Neural Network Architectures for Pneumonia Detection in chest X-Rays.

The data is 5,863 images of chest X-Rays of pediatric patients from the Guangzhou Women and Children's Medical Center, uploaded on Kaggle.
Since there is only a single source of data, the results of these models cannot be generalized to other chest X-Ray images.

Here we use two methods; one by training on the data itself using a custom built architecture, and also by using transfer-learning by using a model pre-trained on ImageNet.
The architecture chosen for transfer learning is VGG19 and both bottleneck and fine tuning methods were used.
