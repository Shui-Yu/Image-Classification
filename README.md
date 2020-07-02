# Image-Classification

This repository includes four Jupyter notebooks regarding image classification of pipe damages. 

Original Dataset: 
  - 3 classes: Dent/Slit/Hole
  - Training size: 286 (Devided into training and validation set)
  - Test size: 71

[01_cnn.ipynb](01_cnn.ipynb):
  - Constructed 4 Constructed a Convolutional Neural Network models
  - Improved model performance step by step conducting parameter tuning and adding regularization.
  - Obtained best model which has training accuracy 98.6% and test accuracy 83.1%
  
[02_cnn_with_data_augmentation.ipynb](02_cnn_with_data_augmentation.ipynb)
  - Implemented data augmentation by randomly applying width/height shift, brightness and channel shift
  - Resulted in doubline the training set size
  - Achieved training accuracy 100% and test accuracy 88.7%
  
[03_trasfer_learning.ipynb](03_trasfer_learning.ipynb)
  - Conducted transfer learning on VGG-16 model, adjusting the fully connected layers to accommondate my problem
  - Achieved training accuracy 98.1% and test accuracy 90.1%
  
[04_image_cropping.ipynb](04_image_cropping.ipynb)
  - Transformed original dataset to image sequence by cropping 20 images from each original image
 
[05_convlstm.ipynb](05_convlstm.ipynb)
  - Experimented a ConvLSTM model to classify image sequence
  
 
