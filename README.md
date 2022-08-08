# Classifying-Medical-Scans-Using-CNNs-ViTs-and-CoAtNets-

## Abstract -
For this project, we study the problem of classifying Medical Image Scans, which is important in the healthcare
sector for the purposes of diagnosis and analysis. Our primary target contribution is in the application part of the
used models.We analyze the performance of the various standard and pretrained models by testing them on new
domain of dataset. We perform comparative analysis of these models and evaluate their performance based on
the overall accuracy as well as class-wise prediction accuracy. We have collected and augmented the data, used a
baseline CNN architecture and pretrained image models for the purposes of classification. Our results and analysis
indicate that Efficient Net followed by CoAtNet were amongst the best performing models for medical image
classification.

## Introduction -
### Problem Setup : We propose to evaluate the performance of standard Convolutional Neural Networks,
EfficientNets, Vision Transformers and CoAtNets on a new application domain of medical imaging. The
Transformer architecture is typically used in the NLP domain and is only recently picking up some speed in the
Computer Vision domain. By testing these architectures on a different domain of medical imaging, we wanted to
explore:
1. If the results of proposed architectures are able to transfer well to another domain entirely.
2. If Transformers can indeed be used as replacements for CNNs (as is proposed by the authors of the Vision
Transformer architecture) or if it makes more sense to have convolutions with attention layers (as is proposed in
CoAtNets).
We were also interested in finding out how much better/worse these architectures fare against a standard
baseline CNN architecture.
### Experience: The models were trained in a new domain of medical imaging. We used the Medical MNIST dataset,
consisting of roughly 60,000 images belonging to 6 different classes namely - AbdomenCT , BreastMRI
,CXR,ChestCT,Hand,HeadCT.
### Inputs and Outputs: The training input of the model consisted of grayscale images from these 6 distinct categories
and the output of the model is the predicted class, given an image. Dataset -
https://www.kaggle.com/andrewmvd/medical-mnist
