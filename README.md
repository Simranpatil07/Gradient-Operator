# Gradient-Operator

In computer vision, image gradients can be used to extract information from images. Gradient images are created from the original image (generally by convolving with a filter, one of the simplest being the Sobel filter) for this purpose. Each pixel of a gradient image measures the change in intensity of that same point in the original image, in a given direction. To get the full range of direction, gradient images in the x and y directions are computed.

One of the most common uses is in edge detection. After gradient images have been computed, pixels with large gradient values become possible edge pixels. 
