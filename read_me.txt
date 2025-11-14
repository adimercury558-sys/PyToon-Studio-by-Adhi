This project demonstrates how powerful fundamental image-processing techniques can be when applied correctly.
 Without relying on heavy machine learning models, 
the system cartoonizes both images and video streams using core OpenCV operations. 
The pipeline applies color quantization through K-Means clustering, 
which reduces color variations and gives the output its expressive cartoon-like effect. 
A combination of filters—such as bilateral smoothing, contour extraction, edge detection, and erosion—adds definition and enhances the artistic style.

Algorithm Used: K-Means Clustering
Filters Applied: Bilateral Filter, Contours, Erode, Canny Edge Detection

Getting Started

Install any Python version above 3.0.

Install the prerequisites listed above.

Run multi_media.py to convert the inmage to cartoon your webcam feed.

To cartoonify images, open convert_to_cartoon.py, uncomment the last two lines, and execute the script.



Documentation

A detailed explanation of the concepts and implementation can be found here:
https://iot4beginners.com/cartoonize-reality-with-opencv-and-raspberry-pi/