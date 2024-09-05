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

Robots need to see and understand their world to be able to interact with objects and perform useful tasks autonomously. Perception is the essential first step in the process for endowing robots to perform autonomously.  Autonomous robots need to make sense of their sensory observations to represent the world around them – and enable their reasoning and action to a goal. Visual perception with cameras as sensors has matured due to the recent advancements in neural networks – which is especially true for performing visual recognition tasks such as object classification, detection, pose estimation, grasp pose detection, etc. 

This course aims to cover the necessary background of neural-network-based deep learning for robot perception – building on advancements in computer vision and enabling – for enabling robots to dexterously manipulate physical objects. During the first part of this course, students will learn to implement, train and debug their own neural networks. During the second part of this course, students will explore recent emerging topics in deep learning for robot manipulation.  This exploration will include analysis of research publications in the area, building up to reproducing one of these publications for implementation as a final course project.

This course builds on and is indebted to these existing courses (as a “star” and a "fork" in the open source sense):
- [University of Michigan - ROB 498-011 & 599-011: Deep Learning for Robot Perception](https://deeprob.org/w24/){:target="_blank"} instructed by [Xiaoxiao Du](https://xiaoxiaodu.net/){:target="_blank"}, [Anthony Opipari](https://topipari.com){:target="_blank"}, and [Chad Jenkins](https://ocj.name/){:target="_blank"}
- [University of Minnesota - CSCI5980: Deep Learning for Robot Perception and Manipulation](https://rpm-lab.github.io/CSCI5980-Spr23-DeepRob){:target="_blank"} instructed by [Karthik Desingh](https://karthikdesingh.com/){:target="_blank"}, in collaboration with [Anthony Opipari](https://topipari.com){:target="_blank"} and [Chad Jenkins](https://ocj.name/){:target="_blank"} from the University of Michigan.
- [University of Michigan - EECS 498-007 / 598-005: Deep Learning for Computer Vision](https://web.eecs.umich.edu/~justincj/teaching/eecs498/WI2022/schedule.html){:target="_blank"} instructed by [Justin Johnson](https://web.eecs.umich.edu/~justincj/){:target="_blank"}
- [Stanford - CS231n: Deep Learning for Computer Vision](http://cs231n.stanford.edu/index.html){:target="_blank"} instructed by [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li){:target="_blank"} and [Andrej Karpathy](https://karpathy.ai/){:target="_blank"}

## Topics and Course Structure

The first half of the course will cover deep learning fundamentals leaning toward computer vision tasks catered to robot perception problems.

- Image classification, Linear classifiers
- Regularization and optimization
- Fully-connected neural networks, Backpropagation
- Convolutional neural networks, Network architectures
- Training neural networks
- Object detection
- Semantic segmentation 
- Imitation learning

The second half of the course will switch to seminar style covering following advanced topics in robot perception and manipulation via discussing publications.

- RGBD perception and network architectures
- Transformer architecture(s)
- Object perception for robot manipulation
  - Rigid object perception
  - Instance-level object pose estimation
  - Category-level object pose Estimation
  - Dense object descriptors
  - Grasp pose estimation
- Visual pre-training for robot manipulation
- Diffusion models for policy learning
- Visual-Language models
- Multimodal learning for robot manipulation


## Prerequisites

- Strongly encouraged prerequisites:
  - Linear Algebra, Calculus, and Probability
  - Programming fluency in data structures in a classical programming language is essential.  
  - Prior experience with the [Python programming language](https://www.python.org/) is strongly recommended.

- Recommended prerequisites: 
  - CSCI 5511 - Artificial Intelligence I
  - CSCI 5521 - Machine Learning Fundamentals
    - Familiarity with concepts from machine learning will be helpful.
  - CSCI 5551 - Introduction to Intelligent Robotic Systems

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
- Health reasons: Email kdesingh@umn.edu before the lecture with the reason to attend via Zoom, to obtain the meeting ID and password. 

## Discussion Sections

There will be no discussion section for this class. 

## Programming Projects

You will complete 5 programming [projects](/CSCI5980-F24-DeepRob/projects/) over the course of the semester. All projects will be implemented using Python, Pytorch and Google Colab.

## Final Project

Instead of a final exam at the end of the semester, you will complete a final project working in groups of 1 to 3 students.

[TODO] The final project will entail several core deliverables: (1) an in-class team lecture with background and a paper in detail, (2) creating a real-world or simulation setup for robot manipulation task to facilitate data acquisition, (3) neural network architecture development, (4) training objectives and strategies, (5) evaluation of the performance, (6) Video and poster presentation.

The objective of the final project is for you to gain experience with state of the art approaches in deep learning and a sense of how research in the area is conducted.

## Quizzes

Throughout the semester, there will be a total of 16 quizzes administered through [gradescope](){:target="_blank"}. These quizzes will be posted before lecture sections throughout the semester and be available to take until the beginning of lecture that same day. Quizzes will be released at 6:00AM CT and must be submitted by 2:30PM CT. Each quiz will have a 15 minute time limit. Each quiz will consist of 1 or 2 short questions within the scope of previously covered lectures and graded projects.

## Grading Policy

Course grades will be determined according to the following criteria:

 - Project 1 (Linear classfication):         5%
 - Project 2 (Fully-connected and CNNs) :   10%
 - Project 3 (Object detection with CNNs):  10%
 - Project 4 (Object pose estimation):      10%
 - Project 5 (Imitation learning):          10%
 
 - Final Project:
   - In-class presentation background:       5%
   - In-class presentation paper in detail:  5%
   - Data acquisition/Simulation setup:     10%
   - Network development:                    5%
   - Training strategy:                     10%
   - Video and poster:                      10%
 - 20 Pre-Lecture Quizzes:                  10% (0.5% each)

## Collaboration Policy

The free flow of discussion and ideas is encouraged. <b> But, everything you turn in must be your own work </b>, and you must note the names of anyone you collaborated with on each problem and cite resources that you used to learn about the problem. If you have any doubts about whether a particular action may be construed as cheating, ask the instructor for clarification before you do it. Cheating in this course will result in a grade of F for course and the [University policies](https://communitystandards.umn.edu/avoid-violations/avoiding-scholastic-dishonesty) will be followed.

No code can be communicated, including verbally. Explicit use of external sources must be clearly cited.

## Students with Disabilities
If you have a disability for which you are or may be requesting an accommodation, you are encouraged to contact both your instructor and [Disability Resources Center](https://disability.umn.edu/) (DRC).

## Discussion Forum

The [Ed Stem](){:target="_blank"} discussion forum is available for discussion of course materials including lectures and projects. 

<b>Any discussion of quizzes and verbatim code on the Ed Stem forum must be posted privately.</b>