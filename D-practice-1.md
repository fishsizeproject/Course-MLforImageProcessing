---
layout: default
---

<sub>[Course Overview](index.md) > Practice 1: Pre-processing images</sub>

# Practice 1: Pre-processing images 

Framework step 2:

![Framework](./images/framework.png)

In this section we will pre-process images that may contain sensitive data, such as people’s faces. Images collected by citizens or extracted from internet may contain sensitive data and depending on the nature of subsequent work (e.g. crowdsourced annotation of images), it may be preferrable to remove such data. In this practice we will use the function `detect_face()` of the Python library [CVlib](https://www.cvlib.net/) and the pre-trained model `caffemodel` to detect human faces. After face detection, a rectangle is drawn around the face and an overlay is applied to the image content inside the rectangle to remove sensitive data before further analyses.

You can access the notebook here:

 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ad-t1zDnx7_UGXiCahZnvSDfoGjzswb_#scrollTo=2zPqiDyVWEIP)

<br/>



## Resources

[CVlib on Github](https://github.com/arunponnusamy/cvlib) - besides face detection the library has functions for gender detection and other objects detection (such as dog and horse)
