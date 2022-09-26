# for-ai-small-car
ai small car

realy ——
raspberry pi3
small car
pc
camera

environment ——
rasbian
opnecv2.45
numpy

The road detection algorithm used in this program is the most basic detection algorithm, which can be upgraded to the depth learning algorithm, but there is no time to do it. For road detection, the most basic is to randomly extract the upper and lower equal width areas of the image on the image, and calculate the gray scale center of the image. It can be seen that when the difference between the gray scale center of the upper half image and the lower half image center exceeds the threshold, It is determined that the road has turned, and the image center is taken as the coordinate origin. When the interpolation is greater than 0, it means to turn right, and vice versa. It can be set freely.
