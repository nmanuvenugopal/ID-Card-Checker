# ID-Card-Checker
ID Card Checker

* Read the image using CV2.imread function.

* Convert the coloured image to gray scale image.

* I have found the Structural Similarity Score (SSIM score) and Difference image. Lower the SSIM score lower will be chance of images being similar.

* Higher the Difference Image values Lower will be the chances of images being same or similar.

* Using this SSIM score, we will try to find out the threshold values. The treshold function will apply an adaptive treshold and converts the Gray Scale image to the binary sclae image.

* This Threshold values are then used to find out the Contour values using the "findContours" functions and we will then try to grab the contours by using the grab_contours function.

* We will also try to display the difference image and the difference between the two images will be displayed in black.
![image](https://user-images.githubusercontent.com/99719105/218274625-57cc479b-1262-41fc-bafd-4235013861ec.png)

* We will display the threshold image (after applying the enhanced threshold). The white portion indicate the threshold difference between the Original and Tampered Image.
![image](https://user-images.githubusercontent.com/99719105/218274687-08510653-5e4d-4f2d-8665-463aa68ff0d8.png)

* I have also included the flask application which I have used.

* Reference - Build 75 Powerful Data Science & Machine Learning Projects - Pianalytix (Udemy)
