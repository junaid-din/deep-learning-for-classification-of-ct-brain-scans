## Deep Learning for Classification of CT Brain Scans

Created by [Junaid Din](https://github.com/junaid-din)

This project was undertaken as part of an Artificial Intelligence module and in collaboration with a use-case scenario from the NHS. The objective was to develop a deep learning model capable of classifying CT brain scan images into three medical conditions: cancer, tumour, and aneurysm. Using a dataset of 512 images in .jpg and .dcm formats, the study explored and compared the performance of a Convolutional Neural Network (CNN) and a Multilayer Perceptron (MLP) model. The project aimed to investigate the efficacy of these models in medical image classification tasks.

Tasks completed:

* Explored the dataset of 512 brain CT scans (which was assumed balanced across the 3 classes: cancer, tumour, aneurysm).
* Identified key data limitations including no class for "normal" brain scans as well as scans being from the same patient at different angles
* Preprocessed image data: Loaded images, normalized pixel values to range 0–1, encoded labels using LabelEncoder and to_categorical() and split into training and test sets
* Developed CNN and MLP models implementing early stopping to prevent overfitting
* Evaluated both deep learning models and compared results

![DL](images/dl.jpeg)
