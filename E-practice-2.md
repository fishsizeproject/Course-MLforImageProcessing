---
layout: default
---

<sub>[Course Overview](index.md) > Practice 2: Images pre-annotation and annotation</sub>

# Practice 2: Images pre-annotation and annotation 

Framework steps 3 and 4:

![framework](./images/framework.png)

Before we apply computer vision methods, available images must be properly prepared. This includes classification of images into correct groups (i.e. fish species), placing boxes or tracing focus objects in the images and augmenting the data set. Image processing is often done manually and can be time consuming. This is particularly true if images for model training are collected through recreational fishing apps, citizen science or automated ‘scrubbing’ of online sites, as such image collections may include multiple irrelevant images. 

In this section we will partly automate and speed up image processing tasks by pre-annotating images with bounding boxes to reduce the amount of manual work required to process the images and to place bounding boxes. We will use an object detector from the module _inception_resnet_v2_, a Keras image classification [model](https://arxiv.org/abs/1602.07261) pre-trained on [Open Images Dataset V4](https://storage.googleapis.com/openimages/web/index.html) to detect a fish in the image. Note that he pre-trained object detector model will be used to automatically place bounding boxes around the fish shapes but the model can be used to detect 600 different shapes, including elephant, lynx, bird, insect, shellfish, tree, plant and others. 

After placing the bounding box in the fish, we will use a script to format the metadata file cointaining the information on the bounding boxes coordinates. We will convert the bounding boxes coordinates from relative values to absolute values and save the metadata in a _.csv_ file. This step is required to open the images and pre-annotations (bounding boxes) in the [VGG software](https://www.robots.ox.ac.uk/~vgg/software/via/), which we will use yo manually annotate images.

You can access the notebook [here]().

 
<br/>

## VGG software

Finally, the last part of this practice is the manual annotation of images. Note that this step is required only if you are using the object detection method for model training. In this course we will use the classification method which means we will not need the _.csv_ file with annotations.

You will need to download the [VGG software](https://www.robots.ox.ac.uk/~vgg/software/via/) and load the images with the _.csv_ file generated in the step before (pre-annotations).

<br/>


## Resources

[TensorFlow 2 tutorial: quickstart for beginners](https://www.tensorflow.org/tutorials/quickstart/beginner)

