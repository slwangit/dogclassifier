[//]: # (Image References)

[image1]: ./images/front.png "front"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

In this project, I explored how to learn a dog breed classifier. There are hundreds of dog breeds around the world. Even for a normal human, it is hard to recognize each single dog breed. So as deep learning becomes more powerful nowadays, a natural question to ask is can computers achieve this? We will explore various deep learning techniques in this project to see how well a deep neural network can realize the challenging dog breed classification problem.

![front][image1]

## Table of Contents
- [Project Overview](#project-overview)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Project Motivation<a name="motivation"></a>](#project-motivation)
- [File Descriptions<a name="files"></a>](#file-descriptions)
		- [Datasets:](#datasets)
		- [Coding:](#coding)
- [Results](#results)
- [Licensing, Authors, and Acknowledgements<a name="licensing"></a>](#licensing-authors-and-acknowledgements)

## Installation
In this project, the requirements for libraries are mainly image process packages, machine learning, and deep learning packages.The code is recommended to be run using Python version 3.*.

The libraries used:<br>
* numpy<br>
* sklearn<br>
* keras<br>
* glob<br>
* IPython<br>
* cv2<br>
* pillow<br>
* matplotlib.pyplot<br>
* tqdm<br>

You can find the detailed requirements at `requirements/requirements.txt`.

## Project Motivation<a name="motivation"></a>

In this project, I explored how to learn a dog breed classifier. There are hundreds of dog breeds around the world. Even for a normal human, it is hard to recognize each single dog breed. So as deep learning becomes more powerful nowadays, a natural question to ask is can computers achieve this? We will explore various deep learning techniques in this project to see how well a deep neural network can realize the challenging dog breed classification problem.

In this project, I conducted the following steps:
1. Data Preprocessing
2. Build a Simple CNN Model
3. Transfer Learning - Based on Pre-trained Model ResNet-50 and VGG
4. Final Combined Model - Human Face Detection and Dog Breed Classification

## File Descriptions<a name="files"></a>
#### Datasets:
This project contains several test images in the `my_images` folder. The dataset for trianing the simple CNN is too large to be uploaded here.

#### Coding:

TThe main project is in the `dog_app.ipynb`. 
For the whole workflow, results, and interpretation from a technical view, please refer to the `airbnb_analysis.ipynb`.

## Results
The main findings and report can be found in the post available [here](https://medium.com/@slwang0507/dog-breed-classifier-80ef1695eb7f).
The article is friendly for the audience from many fields.

## Licensing, Authors, and Acknowledgements<a name="licensing"></a>
The datasets for this project was obtained from Udacity. You can find licensing and other detailed information in the `LICENSE.txt`.
Also, I must give credit to Stack Overflow for the coding part and Medium for the deep learing knowledge and debuging part. 
All the code here are open to the public. Thus, feel free to use it as you would like.