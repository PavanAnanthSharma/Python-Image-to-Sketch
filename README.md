# Python-Image-to-Sketch


```python
Editor = Pavan Ananth Sharma
```

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Introduction:

In Python, an image is just a two-dimensional array of integers. So one can do a couple of matrix manipulations using various python modules in order to get some very interesting effects. In order to convert the normal image to a sketch, we will change its original RGB values and assign its RGB values similar to grey, in this way a sketch of the input image will be generated. Here we will experiment with multiple approaches to get the best output, lets hope for the best

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Approach 1:

1.Import all required modules (numpy, imageio, scipy.ndimage, OpenCV)
2.Take Image input
3.Check RGB value of image and convert into according to RGB values
4.Show finale image output using cv2.imwrite()


