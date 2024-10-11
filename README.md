Overview
This project implements the Canny edge detection algorithm, a widely used technique in image processing for detecting edges in images. The Canny algorithm is known for its effectiveness in detecting a wide range of edges while minimizing noise. It involves several steps, including noise reduction, gradient calculation, non-maximum suppression, and edge tracking by hysteresis.

Canny Edge Detection Algorithm
Noise Reduction: The algorithm begins by applying a Gaussian filter to the image to reduce noise and smooth it out.
Gradient Calculation: It calculates the gradient intensity and direction for each pixel using Sobel operators, highlighting regions with strong intensity changes.
Non-Maximum Suppression: This step thins out the edges by suppressing non-maximum pixels in the gradient direction, retaining only the most prominent edges.
Edge Tracking by Hysteresis: Finally, it uses two thresholds to identify strong and weak edges. Strong edges are retained, while weak edges are included only if they are connected to strong edges.

Requirements
Python 3.x
OpenCV
NumPy
