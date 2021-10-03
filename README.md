# Image Caption Generator

Image captioning is the task of generating textual descriptions of a given image, requiring techniques of computer vision and natural language processing.

## Description

It is a popular research area of Artificial Intelligence that deals with image understanding and a language description for that image. Generating well-formed sentences requires both syntactic and semantic understanding of the language. Being able to describe the content of an image using accurately formed sentences is a very challenging task, but it could also have a great impact, by helping visually impaired people better understand the content of images. [Source](https://www.analyticsvidhya.com/blog/2020/11/create-your-own-image-caption-generator-using-keras/)

To generate a caption, I have combined two models **Convolutional Neural Network (CNN)** and **Long short-term memory (LSTM)**

### Model architechture:
![download](https://user-images.githubusercontent.com/55491822/135738726-3ab0d9c4-dadb-4e88-9c58-ec013875675a.png)


## Outcome

![1](https://user-images.githubusercontent.com/55491822/135726645-8fbca07e-a261-47f0-9bf2-ca1ff65fda67.PNG)
![2](https://user-images.githubusercontent.com/55491822/135726651-09ff9298-d459-4121-9286-42603305122c.PNG)
![3](https://user-images.githubusercontent.com/55491822/135726653-2f0ed99e-f8be-45c9-9ba2-379853af1232.PNG)


## Dataset Information

Here, I have used [COCO Dataset 2017](https://cocodataset.org/#download) which contains 12 different types of categories and among them it has 80 types of sub-categories. Each sub categories contain list of images and five captions to each image.

[Dataset download link](https://www.kaggle.com/kamhar/cocods)

## Prerequisite Technical Skills
- Python
- Tensflow
- Keras
- NLTK
- OpenCV

## Kaggle Link
You will get step by step guidence about this project by clicking on this link: 
https://www.kaggle.com/ysthehurricane/image-caption-generator-tutorial
