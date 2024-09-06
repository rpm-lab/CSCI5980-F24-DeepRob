---
layout: page
title: Syllabus
description: Course policies and information pertaining to Deep Learning for Robot Manipulation at the University of Minnesota.
nav_order: 2
---

# Course Syllabus
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About

Robots need to sense and understand their world to be able to interact with objects and perform useful tasks autonomously. Perception is the essential first step in the process for endowing robots to perform autonomously.  Autonomous robots need to make sense of their sensory observations to represent the world around them – and enable their reasoning and action to a goal. Visual perception with cameras as sensors has matured due to the recent advancements in neural networks – which is especially true for performing visual recognition tasks such as object classification, detection, pose estimation, grasp pose detection, etc. While visual perception is becoming more prevalent, robots require perception from other sensory modes too. Especially, in the context of complex robot's interaction on objects - **manipulation** - multiview multimodal sensory perception is shown to be necessary. **Deep learning** has a huge role to play in encoding these sensory observations and learning **manipulation** policies. 

This course covers the necessary background of neural-network-based deep learning for robot perception – building on advancements in computer vision that enable robots to physically manipulate objects. During the first part of this course, students will learn to implement, train and debug their own neural networks. During the second part of this course, students will explore recent emerging topics in deep learning for robot perception and manipulation. This exploration will include analysis of research publications in the area of robot manipulation, building up to reproducing one of these publications for implementation as a final course project.

This course builds on and is indebted to these existing courses (as a “star” and a "fork" in the open source sense):
- [University of Michigan - ROB 498-011 & 599-011: Deep Learning for Robot Perception](https://deeprob.org/w24/){:target="_blank"} instructed by [Xiaoxiao Du](https://xiaoxiaodu.net/){:target="_blank"}, [Anthony Opipari](https://topipari.com){:target="_blank"}, and [Chad Jenkins](https://ocj.name/){:target="_blank"}
- [University of Minnesota - CSCI5980: Deep Learning for Robot Perception and Manipulation](https://rpm-lab.github.io/CSCI5980-Spr23-DeepRob){:target="_blank"} instructed by [Karthik Desingh](https://karthikdesingh.com/){:target="_blank"}, in collaboration with [Anthony Opipari](https://topipari.com){:target="_blank"} and [Chad Jenkins](https://ocj.name/){:target="_blank"} from the University of Michigan.
- [University of Michigan - EECS 498-007 / 598-005: Deep Learning for Computer Vision](https://web.eecs.umich.edu/~justincj/teaching/eecs498/WI2022/schedule.html){:target="_blank"} instructed by [Justin Johnson](https://web.eecs.umich.edu/~justincj/){:target="_blank"}
- [Stanford - CS231n: Deep Learning for Computer Vision](http://cs231n.stanford.edu/index.html){:target="_blank"} instructed by [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li){:target="_blank"} and [Andrej Karpathy](https://karpathy.ai/){:target="_blank"}

## Topics and Course Structure

The first half of the course will cover deep learning fundamentals leaning toward computer vision tasks catered to robot perception problems leading to policy learning.

- Image classification, Linear classifiers
- Regularization and optimization
- Fully-connected neural networks, Backpropagation
- Convolutional neural networks, Network architectures
- Training neural networks
- Object detection
- Semantic segmentation 
- Imitation learning

The second half of the course will switch to seminar style covering following advanced topics in robot perception and manipulation via discussing publications. These topics will be highly related to the final projects the student teams choose to work on. Below are a few topics that could be of interest in this course. 

- Network architectures for other sensing modes
  - RGBD or multiview
  - Point cloud
  - Force/Torque
  - Audio
  - Proprioception
  - Time series data
  - Multisensory perception
- Object perception for robot manipulation
  - Rigid object perception
  - Instance-level and category-level object pose estimation
  - Dense object descriptors
  - Grasp pose estimation
- 3D Perception for robot manipulation
  - Explicit and implicit models
  - Neural radiance fields
  - Guassian spalling
- Transformer architecture(s)
- Visual pre-training for robot manipulation policy learning
- Diffusion models for policy learning
- Visual-Language models for robot manipulation
- Foundational models
- more... 

## Prerequisites

- Strongly encouraged prerequisites:
  - Linear Algebra, Calculus, and Probability
  - Programming fluency in data structures in a classical programming language is essential.  
  - Prior experience with the [Python programming language](https://www.python.org/) is strongly recommended.

- Recommended prerequisites are at least two of the following courses or courses on similar level: 
  - CSCI 5511 - Artificial Intelligence I
  - CSCI 5512 - Artificial Intelligence II
  - CSCI 5521 - Machine Learning Fundamentals
  - CSCI 5525 - Machine Learning: Analysis and Methods
  - CSCI 5527 - Deep Learning: Models, Computation, Applications
  - CSCI 5551 - Introduction to Intelligent Robotic Systems
  - CSCI 5561 - Computer Vision
  - CSCI 5563 - Multiview 3D Geometry in Computer Vision
  - CSCI 5611 - Animation & Planning in Games
  - EE 5561 - Image Processing and Applications
  - EE 5940 - Robot Vision

## Textbook

There is no required textbook for this course, however optional readings will be suggested from the textbook, ["Deep Learning" by Ian Goodfellow and Yoshua Bengio and Aaron Courville](https://www.deeplearningbook.org){:target="_blank"}.

For additional references, consider the following textbooks:

“[Introduction to Robotics and Perception](https://www.roboticsbook.org/)” by Frank Dellaert and Seth Hutchinson
“[Robotics, Vision and Control](https://link.springer.com/book/10.1007/978-3-642-20144-8)” by Peter Corke
“[Computer Vision: Algorithms and Applications](http://szeliski.org/Book/)” by Richard Szeliski
“[Foundations of Computer Vision](https://mitpress.mit.edu/9780262048972/foundations-of-computer-vision/)” by Antonio Torralba, Phillip Isola, and William T. Freeman

## Lectures

Lectures will take place in-person on **Mondays and Wednesdays from 9:45-11:00 AM CT in Appleby Hall 102**. 
Remote access will be made available for the following reasons:
- Weather impediment: Zoom link will be sent out via email prior to the lecture

## Discussion Sections

There will be no discussion section for this class. 

## Programming Projects

You will complete 5 programming [projects](/CSCI5980-F24-DeepRob/projects/) over the course of the semester. All projects will be implemented using Python, Pytorch and Google Colab.

## Final Project

Instead of a final exam at the end of the semester, you will work on a final project through out the semester. After a few weeks on reading and brainstorming excercises, a team will be formed for the final project. Each team will have 2 to 3 students. 

This semester-long activity for the final project will entail several activities and deliverables: (1) brainstorming exercises, (2) individual paper readings, (3) forming groups, (4) team brainstorming exercises to select the final project, (5) an in-class student team lecture covering background and a detailed paper discussion, (6) creating a real-world or simulation setup for a robot manipulation task to facilitate data collection, (7) neural network architecture development, (8) defining training objectives, strategies, logging, and progress visualization, (9) evaluation of both training and task performance, and (10) creating a final video and presenting a poster.

The objective of the final project is for you to gain experience with state-of-the-art approaches in deep learning for robot manipulation and develop a sense of how research in the area is conducted..

## Grading Policy

Course grades will be determined according to the following criteria:

 - Project 0 (optional and **not graded**)
 - Project 1 (Linear classfication):         5%
 - Project 2 (Fully-connected and CNNs) :   10%
 - Project 3 (Object detection with CNNs):  10%
 - Project 4 (Object pose estimation):      10%
 - Project 5 (Imitation learning):          10%
 
 - Final Project:
   - Individual brainstorming and reading:   5%
   - In-class presentation background:       5%
   - In-class presentation paper in detail:  5%
   - Data acquisition/Simulation setup:     10%
   - Network development:                   10%
   - Training strategy and evaluation:      10%
   - Video and poster:                      10%

## Collaboration Policy

The free flow of discussion and ideas is encouraged. <b> But, everything you turn in must be your own work </b>, and you must note the names of anyone you collaborated with on each problem and cite resources that you used to learn about the problem. **If you have any doubts about whether a particular action may be construed as cheating, ask the instructor for clarification before you do it.** Cheating in this course will result in a grade of F for course and the [University policies](https://communitystandards.umn.edu/avoid-violations/avoiding-scholastic-dishonesty) will be followed.

No code can be communicated, including verbally. Explicit use of external sources must be clearly cited in your presentations and code.

## Students with Disabilities
If you have a disability for which you are or may be requesting an accommodation, you are encouraged to contact both your instructor and [Disability Resources Center](https://disability.umn.edu/) (DRC).

## Discussion Forum

The [Ed Stem](https://edstem.org/us/courses/66160/discussion/){:target="_blank"} discussion forum is available for discussion of course materials including lectures and projects. 

<b>Any discussion of quizzes and verbatim code on the Ed Stem forum must be posted privately.</b>