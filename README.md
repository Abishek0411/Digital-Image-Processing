# Digital-Image-Processing
## Poisson Noise and Gaussian Filter
### Problem Statement:
Identify the size of the landslide image. Resize the image (17x17). Apply poison noise in the image, Print the output. Remove poison noise from Image using Gaussian filter and show the final result.
### Algorithm:
1.	Read the input landslide image using the appropriate function (imread).
2.	Determine the size of the input landslide image using the size function.
3.	Resize the image to 17x17 pixels using the imresize function.
4.	Apply Poison noise to the resized image using the imnoise function with the 'poisson' option.
5.	Use a Gaussian filter to remove the poison noise from the noisy image. You can achieve this using the imgaussfilt function. Adjust the standard deviation of the Gaussian filter as needed to control the amount of noise removal (We have taken it to be ‘2’).
6.	Display the resized image, noisy image, and filtered image using the imshow function.
