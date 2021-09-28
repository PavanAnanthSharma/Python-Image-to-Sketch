# Python-Image-to-Sketch


```python
Editor = Pavan Ananth Sharma
```

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Introduction:

In Python, an image is just a two-dimensional array of integers. So one can do a couple of matrix manipulations using various python modules in order to get some very interesting effects. In order to convert the normal image to a sketch, we will change its original RGB values and assign its RGB values similar to grey, in this way a sketch of the input image will be generated. Here we will experiment with multiple approaches to get the best output, lets hope for the best

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Approach 1:

* Import all required modules (numpy, imageio, scipy.ndimage, OpenCV).
* Take Image input.
* Check RGB value of image and convert into according to RGB values.
* Show finale image output using cv2.imwrite().

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Approach 2:

```
pip install cv2
```
* Then we will import cv2 inside our code, after that, we will use some of the following functions, so we use ``` import * from cv2``` or ``` import cv2```
*  imread()- This function will load the image i.e in the specified folder. 
*  cvtColor()- This function takes color as an argument and then changes the source image color into that color.
*  bitwise_not()- This function will help the image to keep the properties as same by providing the masking to it.
*  GaussianBlur()- This function is used to modify the image by sharpening the edges of the image, smoothen the image, and will minimize the blurring property.
*  divide()- This function is used for the normalization of the image as it doesn’t lose its previous properties.
*  Finally will save the image using imwrite() function.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

