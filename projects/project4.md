---
layout: page
title: Project 4
parent: Projects
nav_order: 5
---
 
# Project 4

## Overview
The objective of this project is to gain experience building and training convolutional neural networks for 6 degrees-of-freedom rigid body pose estimation. In this project you will implement a version of [PoseCNN](https://arxiv.org/abs/1711.00199){: target="_blank" rel="noopener noreferrer"} for object pose estimation.

### The goals for this project are as follows:
 - Implement the [PoseCNN](https://arxiv.org/abs/1711.00199){: target="_blank" rel="noopener noreferrer"} architecture for object pose estimation.
 - Understand the characteristics of neural network based object pose estimation using the [PROPS Pose Dataset](/CSCI5980-F24-DeepRob/datasets/props-pose/).
 - Gain experience reimplementing network architectures by translating from text and figure descriptions to code implementations.


## Instructions

1. <b>Download the project starter code</b>
    - [Project 4 starter code: P4.zip](https://drive.google.com/file/d/1JW7XMXlClBwfwYs2jTcjjQE-vHaVsyY0/view?usp=sharing)

2. <b>Unzip the starter code and upload to Google Drive</b>
    - Once unzipped, you should find a root directory titled 'P4'. The 'P4' directory contains all starter code and files needed to complete this project. Please upload the 'P4' directory to your [Google Drive](https://drive.google.com/){: target="_blank" rel="noopener noreferrer"}.

3. <b>Open the `*.ipynb` and `*.py` files and implement features</b>
    - We recommend implementing the features in a Google Colab environment. The Colab development environment can be accessed by double-clicking on each `*.ipynb` and `*.py` file within your Drive. Instructions for each feature are included in the `pose_estimation.ipynb` file.

    - We suggest starting by implementing the required features as they appear in the `pose_estimation.ipynb` notebook.

    - While working on the project, keep the following in mind:

        - The notebook and the python file have clearly marked blocks where you are expected to write code. <b>Do not write or modify any code outside of these blocks.</b>
        - <b>Do not add or delete cells from the notebook.</b> You may add new cells to perform scratch computations, but you should delete them before submitting your work.
        - <b>Run all cells, and do not clear out the outputs, before submitting.</b> You will only get credit for code that has been run.
        - To avoid experiencing Colab usage limits, save and close your notebooks once finished working.

4. <b>Submit your implementation for Autograder feedback</b>
	- Once you have implemented a portion of the required features, you may submit your work for feedback from the Autograder. To receive feedback, download your `*.ipynb` and `*.py` files then upload them to the [Project 4 Autograder](https://cse-ag-csci5980.cs.umn.edu/web/project/9). You may submit to the Autograder for feedback up to 5 times per day.

5. <b>Download final implementation</b>
    - After implementing all features, <b>save your work</b> and download the completed `*.ipynb` and `*.py` files. 
    - The last cell of the `pose_estimation.ipynb` notebook will generate a `uniqueid_umid_P4.zip` file. The zip file should include `pose_estimation.ipynb`, and `pose_cnn.py` for this assignment.

6. <b>Submit your python and notebook files for grading</b>
    - Upload your files to the [Autograder](https://cse-ag-csci5980.cs.umn.edu/web/project/9) for grading consideration. Your highest score will be used for final grades.

## Deadline

This project is due on <b>Wednesday, November 13th at 11:59pm CT</b>. We suggest starting as soon as possible.

## Grading

This project will be graded by the [Autograder](https://cse-ag-csci5980.cs.umn.edu/web/project/4).