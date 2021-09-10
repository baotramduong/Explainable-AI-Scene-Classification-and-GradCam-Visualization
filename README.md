# Explainable AI Scene Classification with Residual Convolutional Neural Network (ResNet) and Grad-CAM Visualization

## Blog

[Medium Blog](https://baotramduong.medium.com/explainable-ai-scene-classification-with-resnet-18-and-grad-cam-visualization-17ae6d65bb0)

## Introduction

In this project, we will build and train a Deep Convolutional Neural Network (CNN) and Residual Blocks to detect the type of scenery in an image. In addition, we will also use a technique known as Gradient-Weighted Class Activation Mapping (Grad-CAM) to visualize the regions of the inputs and help us explain how our CNN models think and make decision.

## Exploratory Data Analysis

<img src = '../main/Data & Images/images.png' >

<img src = '../main/Data & Images/class_distribution_train.png' >

## Modeling

### Model Architect

<img src = '../main/Data & Images/res-block.png' height='75%' width='75%'>

<img src = '../main/Data & Images/conv_identity_block.png' height='75%' width='75%'>

### Model Evaluation

<img src = '../main/Data & Images/acc_loss_curve.png'  height='75%' width='75%'>

<img src = '../main/Data & Images/classification_report.png' height='75%' width='75%'>

<img src = '../main/Data & Images/cm.png'  height='75%' width='75%' >

<img src = '../main/Data & Images/prediction_result.png' >

## Grad-CAM

<img src = '../main/Data & Images/gradcam_visualization.png' >

## Future Work

* Try other approaches to explain CNN outputs such as: Activations Visualization, Vanilla Gradients, Occlusion Sensitivity, CNN Fixations, and Class Activation Mapping (CAM).

* Apply Transfer Learning

## Reference

Ahmed, R. (n.d.). Explainable AI: Scene Classification and GradCam Visualization [MOOC]. Coursera. https://www.coursera.org/projects/scene-classification-gradcam

Explainable AI. IBM. (n.d.). https://www.ibm.com/watson/explainable-ai.

He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep Residual Learning for Image Recognition. 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 770–778.

King, J., Kishore, V., Ranalli, F. (2017). Scene classification with Convolutional Neural Networks. 

Rosebrock, A. (2020, March 9). Grad-CAM: Visualize Class Activation Maps with Keras, TensorFlow, and Deep Learning. PyImageSearch. Retrieved September 10, 2021, from https://www.pyimagesearch.com/2020/03/09/grad-cam-visualize-class-activation-maps-with-keras-tensorflow-and-deep-learning/. 
