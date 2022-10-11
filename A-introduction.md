---
layout: default
---

<sub>[Course Overview](index.md) \> Introduction</sub>

# Introduction

In this section, participants will find information on course contents, requirements and resources.

The main **learning objectives** of this course are to:

-   Understand the fundamentals of Machine Learning (such as the difference between supervised and unsupervised Machine Learning),

-   Understand a general Machine Learning modelling workflow,

-   Pre-process and pre-annotate images to accelerate ML projects,

-   Apply data augmentation techniques and

-   Build an image classification model with your own or example data.

<br/>

## Programming skills and Python

It will be useful if course participants have basic programming experience, in Python or R. The scripts used in the course are written in Python, but they are adapted to be user friendly and do not require prior Python knowledge to run them (you would naturally need Python knowledge to modify these scripts further). If you want to learn more about coding with Python a few useful tutorials of basic operations can be found [here](https://www.learnpython.org/). You can also find a list of books [here](https://wiki.python.org/moin/IntroductoryBooks).

<br/>

## Google Colab

For this course we will use Google Colab. Colab, or "Colaboratory", is a free, cloud-based environment similar to Jupyter's network environment that allows you to write and execute Python code in your browser without the need for installation and configuration. It also provides some free access to computing resources (GPUs).

To start using Google Colab, you will need a Google account.

We will share notebooks with you and you will be able to create a copy of notebooks in your own Google directory, and then modify and use them for your own purposes.

You can find these badges on each practice session, which will direct you to the session notebook:

<img src="./images/colab_badge.png" alt="colab_badge" width="150"/>

This will open a new editable view of the notebook, which you can run and modify directly without worrying about overwriting the source notebook. To save any changes you make to the notebook you will have to save a copy of the notebook in your own Google Drive. If you try to save the changes directly in the source notebook you will get the message below: 

![colab_notebook_permissions](./images/colab_notebook_permissions.png)

After modifying your notebook you can save changes by choosing `File`→`Save a copy in Drive` and follow the resulting prompts.

Alternatively, you can start your own notebook by going to Google Colab's home page [here](https://colab.research.google.com/) and clicking 'new notebook' on the bottom right corner. If you like you can also click 'cancel' and go to a short tutorial on how to get started with Google colab.

<br/>

## Image datasets

We will provide an example dataset for the course. This dataset includes three fish species with 50 images per species. The images were provided by [MyCatch](https://mycatch.ca/) and [Fishial](https://fishial.ai/). It would be very interesting and exciting if course participants also bring their own datasets of fish images. Ideally you would have at least 50 images per species and you can use as few as two species to start with. Of course more images per species are likely to give you a better model, especially if species are very similar morphologically. However, we will have limited computing resources and time during the course, so it might be good to limit your images to a maximum of 200 per species. It is very important that fish species (or ecotypes or any other classes you want your model to identify) in your dataset are identified correctly, otherwise your model will not be very useful (you might have heard the expression "garbage in - garbage out"). If you are bringing your own dataset please upload images (in JPEG or PNG format) to your Google drive by species (i.e. one species per folder - please make sure these are correctly identified), following this directory structure:


<pre>
<b>dataset</b>
|__ <b>perch</b>
    |______ 100080576_f52e8ee070_n.jpg
    |______ 14167534527_781ceb1b7a_n.jpg
    |______ ...
|__ <b>striped_bass</b>
    |______ 10043234166_e6dd915111_n.jpg
    |______ 1426682852_e62169221f_m.jpg
    |______ ...
|__ <b>trout</b>
    |______ 102501987_3cdb8e5394_n.jpg
    |______ 14982802401_a3dfb22afb.jpg
    |______ ...
|__ ...
</pre>


If your images can be shared publicly and you want to contribute them to the general broader species identification model, such as the one developed by [Fishial](https://fishial.ai/), please [let us know](catari.bio@gmail.com). This way we can start building a global community contributed fish species identification model.

<br/>

## Discussion forum

Course participants are welcome to ask questions and discuss experiences online using the discussion forum in the [course GitHub page](https://github.com/fishsizeproject/Course-MLforImageProcessing/discussions/). You will need a [Github account](https://github.com/join) to post to the discussion forum.

<br/>

## Github

If you are familiar with GitHub, you can create a fork of the course materials to your GitHub account and then open the GitHub hosted notebooks in Colab.

To save a Colab notebook to GitHub requires giving Colab permission to push the commit to your repository. To save changes to your GitHub forked repository you need to go to `File`→`Save a copy to GitHub` and follow the resulting prompts.

We are keen to improve and advance this Machine Learning species identification model framework, so if you would like to collaborate on the [FishSizeProject](https://fishsizeproject.org/), please [contact us](catari.bio@gmail.com).

<br/>
