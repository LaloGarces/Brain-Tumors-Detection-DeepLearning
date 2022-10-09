# Brain-Tumors-Detection-DeepLearning

## In this colab notebook, I use part of the code of one of the lessons of Dr. Ryan Ahmed, using deep learning, in specific ResNet & ResUNet to classify brain tumors images.

I made some comments within the notebook to understand the methood and the maths behind the algorithms. 

![This is an Image](https://raw.githubusercontent.com/LaloGarces/Brain-Tumors-Detection-DeepLearning/main/Brain%20Tumors%20Detection%20Final%20Results.png)

#### Important points to mention ####

- We're going to use an open data source from Kaggle: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation
- **ResNet** (Residual Neural Network) is an artificial neural network (ANN) that skip connections or shortcuts used to jump over some layers (HighwayNets may also learn the skip weights themselves through an additional weight matrix for their gates). For more info, refer please to: https://en.wikipedia.org/wiki/Residual_neural_network & https://arxiv.org/pdf/1512.03385.pdf
- **ResUNet** infers sequentially the boundary of the objects, the distance transform of the segmentation mask, the segmentation mask and a colored reconstruction of the input. For more info, refer please to: https://arxiv.org/abs/1904.00592
- **Image segmentation** is a method of dividing a digital image into subgroups called image segments, reducing the complexity of the image and enabling further processing or analysis of each image segment. Image segmentation is a function that takes image inputs and produces an output.
- 
