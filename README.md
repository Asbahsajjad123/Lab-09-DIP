# Lab-09-DIP
1.	Extract R, G, B channels.
2.	Convert RGB → HSV, YCbCr, Lab.
3.	Apply white balance correction.
4.	Perform color masking.
5.	Compare segmentation strength of color spaces.
# Code Explanation
This lab demonstrates basic color image processing techniques using OpenCV and Python. First, an image is uploaded (with support for Google Colab, Jupyter, or local Python), read, converted from BGR to RGB, and displayed. The RGB image is then split into its individual Red, Green, and Blue channels to observe how each channel represents image intensity. Next, the image is converted into different color spaces—HSV, YCbCr, and Lab—to show how color information can be represented in alternative ways. A white balance operation using the Gray World assumption is applied to correct color bias by equalizing the average intensity of all three channels. After that, color masking is performed in the HSV color space to detect and segment red-colored regions using defined hue ranges. Finally, segmentation results from three different color spaces (RGB, HSV, and Lab) are compared by applying simple thresholding, demonstrating how segmentation quality varies depending on the chosen color model.
