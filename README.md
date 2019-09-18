# Object-detection-using-OpenCV
Overview

We'll use OpenCV to detect a strawberry in an image. We'll perform a series of operations which i've documented in the code to eventually highlight
the biggest strawberry in an image and then draw a green circle around it.

Dependencies

* openCV
* matplotlib
* numpy
* math

You can use [pip](https://pip.pypa.io/en/stable/) to install any missing dependencies. And you can install OpenCV using
[this](http://docs.opencv.org/2.4/doc/tutorials/introduction/table_of_content_introduction/table_of_content_introduction.html) 
guide.

Usage

Run `python demo.py` to create a new image with the detected strawberry. The last 3 lines at the bottom of demo.py let you
define the input image name and the output image name. This detection takes a split second. Deep learning would be more 
accurate but requires more computation currently. Sometimes you just need to quickly detect an image and don't 
mind handcrafted which features to look for.
