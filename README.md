This software was created by MATLAB 2022a.
This software is designed to create pseudo lumbar spine X-ray images from the CT images in the following paper. If you wish to use this software in your research, please include the following paper as a reference.

Development of a Method for Estimating the Angle of Lumbar Spine X-ray Images Using Deep Learning with Pseudo X-ray Images Generated from Computed Tomography.
Ryuma  Moriya, Takaaki Yoshimura, Minghui Tang, Shota Ichikawa, Hiroyuki Sugimori. 
Applied Sciences; 2024.

1.	Specify   the center of the spinal canal and the spinous process in the axial section image of the third lumbar vertebra, thereby creating a reference line for the angle;
2.	The axial section image is converted to a coronal section image, and the range is set so that the first to the fifth lumbar vertebrae are included in the image;
3.	Cut out the set area in the plane perpendicular to the created reference line;
4.	Create a pseudo X-ray image containing three-dimensional information by adding together the images cut out in step 3 to an arbitrary extent;
5.	Visually adjust the maximum and minimum pixel values of the image to create an image with contrast similar to the actual X-ray image;
6.	Create and save an image according to the procedure described up to step 5, rotated in 5° increments from −60° to 60° relative to the reference angle.


