# *In the name of Allah the Merciful*

# Visual Perception for Self Driving Cars - Week 1

## Course Objectives
> This course will introduce you to the main perception tasks in autonomous driving, static and dynamic object detection, and will survey common computer vision methods for robotic perception.  By the end of this course, you will be able to work with the pinhole camera model, perform intrinsic and extrinsic camera calibration, detect, describe and match image features and design your own convolutional neural networks.  You'll apply these methods to visual odometry, object detection and tracking, and semantic segmentation for drivable surface estimation. These techniques represent the main building blocks of the perception system for self-driving cars.

> This is an advanced course, intended for learners with a background in computer vision and deep learning. To succeed in this course, you should have programming experience in Python 3.0, and familiarity with Linear Algebra (matrices, vectors, matrix multiplication, rank, Eigenvalues and vectors and inverses).

## Table of Contents
* ![Course Topics](# Course Topics)
* ![Recommended Textbooks](# Recommended Textbooks)
* ![The Camera Sensor](#The Camera Sensor)
  * ![The Camera Sensor Lesson][#The Camera Sensor Lesson]
  * ![Camera Projective Geometry][#Camera Projective Geometry]
* ![Camera Calibration](# Camera Calibration)
* ![Visual Depth Perception](#Visual Depth Perception)
  * ![Visual Depth Perception Stereopsis]
  * ![Visual Depth Perception - Computing The Disparity]
* ![Image Filtering](#Image Filtering)

## Course Topics
* Module 1: Basics of 3D Computer Vision
  * How Images Are Formed
  * Camera Projective Geometry
  * Camera Calibration
  * 3D Point Cloud Generation to Stereovision
  * Image Processing With Common Image Filters
* Module 2: Extract Useful Information (Features) From Images Through Hand Engineering Features
  * How to Extract Features (Features Detection)
  * Provide Them With Descriptors (Description)
  * How to Match These Features With Each other (Matching)
  * Localize The Camera Through The Above Processes (Visual Odometry)
* Module 3: Feedforward and CNNs
  * The Building Blocks of Feed Forward Neural Networks
  * How to Train NN's and Evaluate Their Performance
* Module 4: Use NN's to Perform 2D Object Detection
  * Problem Formulation
  * CNN's For 2D Object Detection
  * Training vs. Inference
  * Use 2D Object Detection Results to Predict 3D Position and Track Objects on The Road 
* Module 5: Semantic Segmentation
  * Problem Formulation
  * CNN's For Semantic Segmentation
  * Use SS Output For SDC 
  
## Recommended Textbooks     
     > [Forsyth]  -- Forsyth, David A., and Jean Ponce. "A modern approach." Computer vision: a modern approach (2003): 88-101.
     > [Goodfellow] -- Goodfellow, I., Bengio, Y., Courville, A., & Bengio, Y. (2016). Deep learning (Vol. 1). Cambridge: MIT press. PDF available online: (https://www.deeplearningbook.org/)
     > [Szeliski] -- Szeliski, R. (2010). Computer vision: algorithms and applications. Springer Science & Business Media. PDF available online: (http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf)
     > [Hartley] -- Hartley, R., & Zisserman, A. (2003). Multiple view geometry in computer vision. Cambridge university press

## The Camera Sensor



