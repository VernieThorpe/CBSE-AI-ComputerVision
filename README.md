# CBSE-AI-ComputerVision
CBSE Class10 Computer Vision Projects

# Image Transformations using OpenCV

Note: You can learn about this topic from the official OpenCV documentation [here](https://docs.opencv.org/4.x/da/d6e/tutorial_py_geometric_transformations.html).

#### Introduction
Image transformation is a coordinate-changing function that transforms (x, y) coordinates in one coordinate system to (x', y') points in another.

![image.png](attachment:image.png)

> For example, if we plot the same point in u-v coordinate with (2, 3) points in x-y coordinate, the same point is represented in multiple ways, as illustrated below:

> ![image.png](attachment:image.png)

## The Use of Image Transformation
The geometric relationship between the comic book and the image on the right is based on the similarity transformation in the image below (rotation, translation and scaling). If we want to train a machine learning model to find this comic book, we'll need to change the form and angle of the image.

![image.png](attachment:image.png)

In the preprocessing phase of images for machine learning, image alteration techniques can be extremely useful.

> Matrices can be used to represent images. A pixel value at a certain coordinate is represented by each value in a matrix. Matrix multiplication can be used to make image transformations. Mathematicians have devised a set of matrices that can be utilised to perform various transformations.

## Table of contents:

- Image Translation
- Image Scaling
- Image Shearing
- Image Reflection
- Image Rotation
- Image Cropping
