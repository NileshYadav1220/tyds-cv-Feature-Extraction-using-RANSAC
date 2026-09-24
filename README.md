Practical 7: Feature Extraction using RANSAC
Aim

To detect and match features between two images and remove incorrect matches using the RANSAC algorithm.

Technologies Used
Python
OpenCV
NumPy
SIFT
RANSAC
How it works
Read two images.
Convert the images into grayscale.
Detect features using SIFT.
Match the features between both images.
Select good matches.
Use RANSAC to remove incorrect matches.
Display the final feature matches.
Run
python ransac.py
Input
image1.jpg
image2.jpg
Output

The program displays the matching features between the two images after removing incorrect matches using RANSAC.
