# Computer Vision Finding Lane Lines

This is part of the "The Complete Self-Driving Course". In this part finding lanes on an image or video was the goal.

Following steps were done on the image:

![alt text](https://github.com/sboenisch/Computer-Vision-Finding-Lane-Lines/blob/master/test_image.jpg "Example road picture")

* Grayscale: Transform colored picture into a grayscale one.
* Smoothing image: Using Gaussian to reduce noise.
* Edge Detection: Use Canny Edge Detection Function from OpenCV.
* Region of Interest: Mask the region of interest in the picture.
* Line Detection - Hough Transform:
* Optimizing
