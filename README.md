# Stereo-Image-Correspondences-using-Fundamental-Matrix
To learn what is a Fundamental Matrix: https://docs.opencv.org/master/da/de9/tutorial_py_epipolar_geometry.html  
## The Problem Statement of the Assignment is as follows:  
1. Take a stereo image pair of static scene as the input.  
2. Estimate fundamental matrix between the stereo images.  
3. For each point in the reference image, compute epipolar line in the source image.  
4. Search along the epipolar line in the source image to find the corresponding point of each location of the reference image.  
5. Create an image which is geometrically similar to the reference image using the image patches of the source image.  
6. Show the comparison between the results obtained using in-built function and your implementation for the estimation of fundamental matrix.  
7. Show results for atleast 5 stereo pairs.  

Note: In-built functions can be used for feature extraction and description using SIFT/SURF/ORB. Feature Matching and Fundamental matrix should be implemented from scratch. No marks will be awarded for late submission even if it is delayed by few seconds.

The commented code, report and results have been provided. My code from scratch outperformed the inbuilt procedure in python for some images. The inbuilt function outputs have been provided only for few images.   

## References:
Dataset: [1] https://vision.deis.unibo.it/fede/ds-stereo-lab.html  
[2] https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_calib3d/py_epipolar_geometry/py_epipolar_geometry.html
