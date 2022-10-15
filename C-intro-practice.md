---
layout: default
---

<sub>[Course Overview](index.md) \> Intro Practice: Basics of computer vision with Python</sub>

# Intro Practice: Basics of computer vision with Python

<br/>

This course uses a computer vision and ML image analysis framework described in detail in this [publication](https://www.biorxiv.org/content/10.1101/2022.06.29.498112v1.abstract).

![concepts](./images/framework.png)

This open-source modular framework for large scale image storage, handling, annotation and automatic classification, uses cost- and labour-efficient methodologies. The tool is based on [TensorFlow Lite Model Maker library](https://www.tensorflow.org/lite/models/modify/model_maker) and includes data augmentation and [transfer learning](https://books.google.pt/books?id=CLyDxgEACAAJ&printsec=frontcover#v=onepage&q&f=false) techniques, [**AA: what is that? We did not define the term convolutional:** applied to different convolutional neural network models\*\*]\*\*

<br/>

In the introductory practice below we will use Python and computer vision libraries for basic image processing. We will learn to read the image, get information about its dimensions and shape and understand the basic idea of how image information is read by computers. You will learn that computers store images as 2D or 3D matrices, depending on whether it is a gray scale or a colour image. While many of these steps are done automatically in many libraries (R language) and modules (Python), it is nevertheless useful to get a basic idea of how computers 'see' and handle images.

We will also write a few simple Python functions to visualise images. You can just follow and execute the code, but if you would like to learn more about writing functions yourself, you can check some tutorials [here](https://www.w3schools.com/python/python_functions.asp).

One of the libraries we will use is this course is [OpenCV](https://opencv.org/). **This library is written in C++, but can be used in Google Colab and has a graphical interface? -- need to explain why this is needed and how it is different from other scripts. Is OpenCV is just a library of Python or is it a different software. Remember many people will come with R background, where modules ar called libraries?** This library is used widely in computer vision, although we will only use a few basic functions to read and display images. If you would like to learn more about the library you can find a short online course [here](https://opencv.org/opencv-free-course/).

The practice is done on Google Colab and you can access the notebook here:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qhc8kgXAwM3k18zgweAsvwIjSG0Qm8lT)

<br/>

<br/>

## Other Resources

Book : [Programming Computer Vision with Python](http://programmingcomputervision.com/downloads/ProgrammingComputerVision_CCdraft.pdf) by Jan Erik Solem
