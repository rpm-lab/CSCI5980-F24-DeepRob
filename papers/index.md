---
layout: page
title: Papers
description: Collection of deep learning research papers with coverage in perception and associated robotic tasks.
nav_order: 5
has_children: false
has_toc: true
---

# Deep Learning Research Papers for Robot Perception, Grasping and Manipulation
{:.no_toc}

A collection of deep learning research papers with coverage in perception and associated robotic tasks. Within each research area outlined below, the course staff has identified a *core* and *extended* set of research papers. The *core* set of papers will form the basis of our seminar-style lectures starting in [week 10](CSCI5980-F24-DeepRob/calendar/#week-10). The *extended* set provides additional coverage of even more exciting work being done within each area. We will keep adding papers discovered by the students and staff during the semester. 

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# RGB-D Architectures

### Core List

- [PoseCNN: A Convolutional Neural Network for 6D Object Pose Estimation in Cluttered Scenes](https://arxiv.org/abs/1711.00199){:target="_blank"}, Xiang et al., 2018

- [A Unified Framework for Multi-View Multi-Class Object Pose Estimation](https://arxiv.org/abs/1803.08103){:target="_blank"}, Li et al., 2018

- [Learning RGB-D Feature Embeddings for Unseen Object Instance Segmentation](https://proceedings.mlr.press/v155/xiang21a/xiang21a.pdf){:target="_blank"}, Li et al., 2020


- [PVN3D: A Deep Point-Wise 3D Keypoints Voting Network for 6DoF Pose Estimation](https://openaccess.thecvf.com/content_CVPR_2020/papers/He_PVN3D_A_Deep_Point-Wise_3D_Keypoints_Voting_Network_for_6DoF_CVPR_2020_paper.pdf){:target="_blank"}, He et al., 2020


### Extended List

- [3D ShapeNets: A Deep Representation for Volumetric Shapes](https://arxiv.org/abs/1406.5670){:target="_blank"}, Wu et al., 2015

- [VoxNet: A 3D Convolutional Neural Network for Real-Time Object Recognition](https://graphics.stanford.edu/courses/cs233-21-spring/ReferencedPapers/voxnet_07353481.pdf){:target="_blank"}, Maturana et al., 2015


- [Multi-view Convolutional Neural Networks for 3D Shape Recognition](https://openaccess.thecvf.com/content_iccv_2015/papers/Su_Multi-View_Convolutional_Neural_ICCV_2015_paper.pdf){:target="_blank"}, Su et al., 2015

- [Volumetric and Multi-View CNNs for Object Classification on 3D Data](https://openaccess.thecvf.com/content_cvpr_2016/papers/Qi_Volumetric_and_Multi-View_CVPR_2016_paper.pdf){:target="_blank"}, Qi et al., 2016

- [Robust 6D Object Pose Estimation with Stochastic Congruent Sets](https://arxiv.org/abs/1805.06324){:target="_blank"}, Mitash et al., 2018


# Pointcloud Processing 

### Core List

- [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/abs/1612.00593){:target="_blank"}, Qi et al., 2017


- [PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space](https://arxiv.org/abs/1706.02413){:target="_blank"}, Qi et al., 2017


- [PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf){:target="_blank"}, Xu et al., 2018

- [DenseFusion: 6D Object Pose Estimation by Iterative Dense Fusion](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_DenseFusion_6D_Object_Pose_Estimation_by_Iterative_Dense_Fusion_CVPR_2019_paper.pdf){:target="_blank"}, Wang et al., 2019


### Extended List

- [3D Object Detection with Pointformer](https://openaccess.thecvf.com/content/CVPR2021/papers/Pan_3D_Object_Detection_With_Pointformer_CVPR_2021_paper.pdf){:target="_blank"}, Pan et al., 2021


# Object Pose, Geometry, SDF, Implicit surfaces

### Core List

- [SUM: Sequential scene understanding and manipulation](https://ieeexplore.ieee.org/abstract/document/8206164){:target="_blank"}, Sui et al., 2017

- [DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.pdf){:target="_blank"}, Park et al., 2019

- [Implicit surface representations as layers in neural networks](https://openaccess.thecvf.com/content_ICCV_2019/papers/Michalkiewicz_Implicit_Surface_Representations_As_Layers_in_Neural_Networks_ICCV_2019_paper.pdf){:target="_blank"}, Michalkiewicz et al., 2019



### Extended List

- [Local Deep Implicit Functions for 3D Shape](https://arxiv.org/abs/1912.06126){:target="_blank"}, Genova et al., 2020

- [Implicit geometric regularization for learning shapes](https://arxiv.org/abs/2002.10099){:target="_blank"}, Gropp et al., 2020



# Dense object descriptors, Category-level representations

### Core List

- [Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation](https://arxiv.org/abs/1806.08756){:target="_blank"}, Florence et al., 2018

- [Normalized Object Coordinate Space for Category-Level 6D Object Pose and Size Estimation](https://geometry.stanford.edu/projects/NOCS_CVPR2019/){:target="_blank"}, Wang et al., 2019

- [kPAM: KeyPoint Affordances for Category-Level Robotic Manipulation](https://arxiv.org/abs/1903.06684){:target="_blank"}, Manuelli et al., 2019

- [Single-Stage Keypoint-Based Category-Level Object Pose Estimation from an RGB Image](https://arxiv.org/abs/2109.06161){:target="_blank"}, Lin et al., 2022 


### Extended List

- [Visual Descriptor Learning from Monocular Video](https://arxiv.org/abs/2004.07007){:target="_blank"}, Deekshith et al., 2020

- [SurfEmb: Dense and Continuous Correspondence Distributions for Object Pose Estimation with Learnt Surface Embeddings](https://arxiv.org/abs/2111.13489){:target="_blank"}, Haugaard et al., 2021

- [Fully Self-Supervised Class Awareness in Dense Object Descriptors](https://proceedings.mlr.press/v164/hadjivelichkov22a.html){:target="_blank"}, Hadjivelichkov et al., 2022


# Recurrent Networks and Object Tracking

### Core List

- [DeepIM: Deep Iterative Matching for 6D Pose Estimation](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yi_Li_DeepIM_Deep_Iterative_ECCV_2018_paper.pdf){:target="_blank"}, Li et al., 2018

- [PoseRBPF: A Rao-Blackwellized Particle Filter for 6D Object Pose Tracking](https://arxiv.org/abs/1905.09304){:target="_blank"}, Deng et al., 2019

- [6-PACK: Category-level 6D Pose Tracker with Anchor-Based Keypoints](https://ieeexplore.ieee.org/abstract/document/9196679){:target="_blank"}, Wang et al., 2020

- [XMem: Long-Term Video Object Segmentation with an Atkinson-Shiffrin Memory Model](https://arxiv.org/abs/2207.07115){:target="_blank"}, Cheng and Schwing, 2022


### Extended List

- [Long Short-Term Memory](https://ieeexplore.ieee.org/abstract/document/6795963){:target="_blank"}, Hochreiter et al., 1997

- [TrackFormer: Multi-Object Tracking with Transformers](https://openaccess.thecvf.com/content/CVPR2022/papers/Meinhardt_TrackFormer_Multi-Object_Tracking_With_Transformers_CVPR_2022_paper.pdf){:target="_blank"}, Meinhardt et al., 2022

<!-- 
# Visual Odometry and Localization

### Core List

- [Backprop KF: Learning Discriminative Deterministic State Estimators](https://proceedings.neurips.cc/paper/2016/file/697e382cfd25b07a3e62275d3ee132b3-Paper.pdf){:target="_blank"}, Haarnoja et al., 2016

- [Differentiable Particle Filters: End-to-End Learning with Algorithmic Priors](http://www.roboticsproceedings.org/rss14/p01.pdf){:target="_blank"}, Jonschkowski et al., 2018

- [Multimodal Sensor Fusion with Differentiable Filters](https://arxiv.org/abs/2010.13021){:target="_blank"}, Lee et al., 2020

- [Differentiable SLAM-net: Learning Particle SLAM for Visual Navigation](https://openaccess.thecvf.com/content/CVPR2021/papers/Karkus_Differentiable_SLAM-Net_Learning_Particle_SLAM_for_Visual_Navigation_CVPR_2021_paper.pdf){:target="_blank"}, Karkus et al., 2021


### Extended List

- [Differentiable Algorithm Networks for Composable Robot Learning](https://arxiv.org/pdf/1905.11602.pdf){:target="_blank"}, Karkus et al., 2019

- [Chasing Ghosts: Instruction Following as Bayesian State Tracking](https://proceedings.neurips.cc/paper/2019/file/82161242827b703e6acf9c726942a1e4-Paper.pdf){:target="_blank"}, Anderson et al., 2019

- [Differentiable Factor Graph Optimization for Learning Smoothers](https://arxiv.org/abs/2105.08257){:target="_blank"}, Yi et al., 2021

- [How to train your differentiable filter](https://link.springer.com/article/10.1007/s10514-021-09990-9){:target="_blank"}, Kloss et al., 2021

- [Differentiable Nonparametric Belief Propagation](https://arxiv.org/abs/2101.05948){:target="_blank"}, Opipari et al., 2021

- [NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields](https://arxiv.org/abs/2210.13641){:target="_blank"}, Rosinol et al., 2022
 -->

# Semantic Scene Graphs and Explicit Representations

### Core List

- [Image Retrieval using Scene Graphs](https://openaccess.thecvf.com/content_cvpr_2015/papers/Johnson_Image_Retrieval_Using_2015_CVPR_paper.pdf){:target="_blank"}, Johnson et al., 2015

- [Semantic Robot Programming for Goal-Directed Manipulation in Cluttered Scenes](https://ieeexplore.ieee.org/abstract/document/8460538){:target="_blank"}, Zeng et al., 2018

- [Differentiable Scene Graphs](https://arxiv.org/abs/1902.10200){:target="_blank"}, Raboh et al., 2020

- [Semantic Linking Maps for Active Visual Object Search](https://arxiv.org/abs/2006.10807){:target="_blank"}, Zeng et al., 2020


### Extended List

- [Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations](https://arxiv.org/abs/1602.07332){:target="_blank"}, Krishna et al., 2016

- [Image Generation from Scene Graphs](https://openaccess.thecvf.com/content_cvpr_2018/papers/Johnson_Image_Generation_From_CVPR_2018_paper.pdf){:target="_blank"}, Johnson et al., 2018

- [3D Scene Graph: A Structure for Unified Semantics, 3D Space, and Camera](https://openaccess.thecvf.com/content_ICCV_2019/html/Armeni_3D_Scene_Graph_A_Structure_for_Unified_Semantics_3D_Space_ICCV_2019_paper.html){:target="_blank"}, Armeni et al., 2020

- [Hydra: A Real-time Spatial Perception System for 3D Scene Graph Construction and Optimization](https://arxiv.org/abs/2201.13360){:target="_blank"}, Hughes et al., 2022


# Neural Radiance Fields and Implicit Representations

### Core List

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934){:target="_blank"}, Mildenhall et al., 2020

- [Object-Centric Neural Scene Rendering](https://arxiv.org/abs/2012.08503){:target="_blank"}, Guo et al., 2020

- [Neural Descriptor Fields: SE(3)-Equivariant Object Representations for Manipulation](https://arxiv.org/abs/2112.05124){:target="_blank"}, Simeonov et al., 2021

- [NeRF-Supervision: Learning Dense Object Descriptors from Neural Radiance Fields](https://yenchenlin.me/nerf-supervision/){:target="_blank"}, Yen-Chen et al., 2022

- [NARF22: Neural Articulated Radiance Fields for Configuration-Aware Rendering](https://arxiv.org/abs/2210.01166){:target="_blank"}, Lewis et al., 2022

- [Learning Multi-Object Dynamics with Compositional Neural Radiance Fields](https://arxiv.org/abs/2202.11855), Driess et al., 2022

### Extended List

- [NeRF Explosion 2020](https://dellaert.github.io/NeRF/){:target="_blank"}, Dellaert, 2020

- [Scene Representation Networks: Continuous 3D-Structure-Aware Neural Scene Representations](https://arxiv.org/abs/1906.01618){:target="_blank"}, Sitzmann et al., 2019

- [Local Implicit Grid Representations for 3D Scenes](https://arxiv.org/abs/2003.08981){:target="_blank"}, Jiang et al., 2020

- [Convolutional occupancy networks](https://arxiv.org/abs/2003.04618){:target="_blank"}, Peng et al., 2020

- [INeRF: Inverting Neural Radiance Fields for Pose Estimation](https://arxiv.org/abs/2012.05877){:target="_blank"}, Yen-Chen et al., 2021

- [ILabel: Interactive Neural Scene Labelling](https://arxiv.org/abs/2111.14637){:target="_blank"}, Zhi et al., 2021

- [BungeeNeRF: Progressive Neural Radiance Field for Extreme Multi-scale Scene Rendering](https://arxiv.org/abs/2112.05504), Xiangli et al., 2021

- [Block-NeRF: Scalable Large Scene Neural View Synthesis](https://arxiv.org/abs/2202.05263){:target="_blank"}, Tancik et al., 2022

- [NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields]([https://arxiv.org/abs/2202.05263](https://arxiv.org/abs/2210.04932)){:target="_blank"}, Byravan et al., 2022



# Datasets

### RGB-D Datasets:

- [(NYU Depth v2) Indoor Segmentation and Support Inference from RGBD Images](https://cs.nyu.edu/~silberman/papers/indoor_seg_support.pdf){:target="_blank"}, Silberman et al., 2012

- [SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite](https://openaccess.thecvf.com/content_cvpr_2015/papers/Song_SUN_RGB-D_A_2015_CVPR_paper.pdf){:target="_blank"}, Song et al., 2015

- [YCB-Video Dataset](https://arxiv.org/abs/1711.00199){:target="_blank"}, Xiang et al., 2018

- [BOP: Benchmark for 6D Object Pose Estimation](https://bop.felk.cvut.cz/home/){:target="_blank"}, Hodaň et al., 2019

- [ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes](http://www.scan-net.org){:target="_blank"}, Dai et al., 2019

- [TO-Scene: A Large-scale Dataset for Understanding 3D Tabletop Scenes](https://arxiv.org/abs/2203.09440){:target="_blank"}, Xu et al., 2022

- [ProgressLabeller: Visual Data Stream Annotation for Training Object-Centric 3D Perception](https://arxiv.org/abs/2203.00283){:target="_blank"}, Chen et al., 2022

### Collecting data with robots:

- [Deep Learning for Robots: Learning from Large-Scale Interaction](https://ai.googleblog.com/2016/03/deep-learning-for-robots-learning-from.html){:target="_blank"}

- [TossingBot: Learning to Throw Arbitrary Objects](https://tossingbot.cs.princeton.edu/){:target="_blank"}

- [All You Need is LUV: Unsupervised Collection of Labeled Images using Invisible UV Fluorescent Indicators](https://arxiv.org/abs/2203.04566){:target="_blank"}, Thananjeyan et al., 2022

### Semantic Datasets:

- [Habitat-Matterport 3D Semantics Dataset](https://arxiv.org/abs/2210.05633){:target="_blank"}, Yadav et al., 2022 

Object Model Datasets:

- [ShapeNet: An Information-Rich 3D Model Repository](https://shapenet.org){:target="_blank"}, Chang et al., 2015

- [PartNet-Mobility Dataset](https://sapien.ucsd.edu/browse){:target="_blank"}


### Simulators:

- [MuJoCo: A physics engine for model-based control](https://ieeexplore.ieee.org/abstract/document/6386109){:target="_blank"}, Todorov et al., 2015

- [Pybullet, a python module for physics simulation for games, robotics and machine learning](https://pybullet.org/wordpress/){:target="_blank"}, Coumans et al., 2015

- [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac-sim){:target="_blank"}

- [Isaac Gym: High Performance GPU-Based Physics Simulation For Robot Learning](https://arxiv.org/abs/2108.10470){:target="_blank"}, Makoviychuk et al., 2021

- [SAPIEN: A SimulAted Part-based Interactive ENvironment](https://sapien.ucsd.edu/){:target="_blank"}

- [Habitat](https://aihabitat.org/){:target="_blank"}

- [iGibson: Interactive Simulation of Large Scale Virtualized Realistic Scenes for Robot Learning](https://svl.stanford.edu/igibson/){:target="_blank"}


# Self-Supervised Learning

### Core List

- [VICRegL: Self-Supervised Learning of Local Visual Features](https://arxiv.org/abs/2210.01571){:target="_blank"}, Bardes et al., 2022

- [Self-Supervised Geometric Correspondence for Category-Level 6D Object Pose Estimation in the Wild](https://kywind.github.io/self-pose){:target="_blank"}, Zhang et al., 2022


# Grasp Pose Detection

### Core List

- [Using Geometry to Detect Grasps in 3D Point Clouds](https://arxiv.org/abs/1501.03100){:target="_blank"}, ten Pas and Platt, 2015

- [Dex-Net 2.0: Deep Learning to Plan Robust Grasps with Synthetic Point Clouds and Analytic Grasp Metrics](https://arxiv.org/abs/1703.09312){:target="_blank"}, Mahler et al., 2017

- [GlassLoc: Plenoptic Grasp Pose Detection in Transparent Clutter](https://ieeexplore.ieee.org/abstract/document/8967685){:target="_blank"}, Zhou et al., 2019

- [Contact-GraspNet: Efficient 6-DoF Grasp Generation in Cluttered Scenes](https://ieeexplore.ieee.org/abstract/document/9561877){:target="_blank"}, Sundermeyer et al., 2021

- [Sample Efficient Grasp Learning Using Equivariant Models](https://arxiv.org/abs/2202.09468){:target="_blank"}, Zhu et al., 2022


### Extended List

- [High precision grasp pose detection in dense clutter](https://ieeexplore.ieee.org/abstract/document/7759114){:target="_blank"}, Gualtieri et al., 2016

- [Grasp Learning: Models, Methods, and Performance](https://arxiv.org/abs/2211.04895){:target="_blank"}, Platt, 2022

# Tactile Perception for Grasping and Manipulation

### Core List

- [Visuotactile Affordances for Cloth Manipulation with Local Control](https://openreview.net/pdf?id=s6NEzqZKaP-){:target="_blank"}, Sunil et al., 2022

- [Tactile Object Pose Estimation from the First Touch with Geometric Contact Rendering](https://arxiv.org/abs/2012.05205){:target="_blank"}, • Bauza et al., 2020

- [ShapeMap 3-D: Efficient shape mapping through dense touch and vision](https://arxiv.org/abs/2109.09884), Suresh et al., 2022

- [More Than a Feeling: Learning to Grasp and Regrasp using Vision and Touch](https://arxiv.org/abs/1805.11085), Calandra et al., 2018 

### Extended List

- [A Review of Tactile Information: Perception and Action Through Touch](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9136877), Li et al., 2020

- [Active Visuo-Haptic Object Shape Completion](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9720238), Rustler et al., 2022

- [Active Extrinsic Contact Sensing: Application to General Peg-in-Hole Insertion](https://arxiv.org/abs/2110.03555), Kim et al., 2021

- [Soft-bubble: A highly compliant dense geometry tactile sensor for robot manipulation](https://arxiv.org/abs/1904.02252), Alspach et al., 2019

- [TACTO: A Fast, Flexible, and Open-source Simulator for High-Resolution Vision-based Tactile Sensors](https://arxiv.org/pdf/2012.08456.pdf), Wang et al., 2020

- [The Feeling of Success: Does Touch Sensing Help Predict Grasp Outcomes?](https://arxiv.org/pdf/1710.05512.pdf), Calandra et al., 2017

- [Learning Self-Supervised Representations from Vision and Touch for Active Sliding Perception of Deformable Surfaces](https://arxiv.org/pdf/2209.13042.pdf), Kerr and Huang et al., 2022

- [GelSight: High-Resolution Robot Tactile Sensors for Estimating Geometry and Force](https://dspace.mit.edu/handle/1721.1/114627), Yuan et al., 2017

- [See, Hear, and Feel: Smart Sensory Fusion for Robotic Manipulation](https://arxiv.org/pdf/2212.03858.pdf), Li et al., 2022


# Pre-training for Robot Manipulation and Transformer Architectures

### Core List

- [SORNet: Spatial Object-Centric Representations for Sequential Manipulation](https://arxiv.org/abs/2109.03891){:target="_blank"}, Yuan et al., 2021

- [Masked Visual Pre-training for Motor Control](https://arxiv.org/abs/2203.06173), Xiao et al., 2022

- [R3M: A Universal Visual Representation for Robot Manipulation](https://arxiv.org/abs/2203.12601), Nair et al., 2022

- [CLIPort: What and Where Pathways for Robotic Manipulation](https://arxiv.org/abs/2109.12098){:target="_blank"}, Shridhar et al., 2021

- [Do As I Can, Not As I Say: Grounding Language in Robotic Affordances](https://say-can.github.io/assets/palm_saycan.pdf){:target="_blank"}, Ahn et al., 2022

- [RT-1: Robotics Transformer for Real-World Control at Scale](https://robotics-transformer.github.io/assets/rt1.pdf){:target="_blank"}, Brohan et al., 2022

### Extended List

- [Interactive Language: Talking to Robots in Real Time](https://arxiv.org/abs/2210.06407){:target="_blank"}, Lynch et al., 2022

- [Transformers are Adaptable Task Planners](https://arxiv.org/abs/2207.02442){:target="_blank"}, Jain et al., 2022

- [CLIP: Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020), Radford et al., 2021

- [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377), He et al., 2021

- [Transporter Networks: Rearranging the Visual World for Robotic Manipulation](https://arxiv.org/abs/2010.14406), Zeng et al., 2020


# Perception Beyond Vision

### Specialized Sensors
{: .no_toc }

- [Pigeons (Columba livia) as Trainable Observers of Pathology and Radiology Breast Cancer Images](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0141357){: target="_blank" rel="noopener noreferrer"}, Levenson et al., 2015

- [Automatic color correction for 3D reconstruction of underwater scenes](https://ieeexplore.ieee.org/abstract/document/7989601){: target="_blank" rel="noopener noreferrer"}, Skinner et al., 2017

- [GelSight: High-Resolution Robot Tactile Sensors for Estimating Geometry and Force](https://www.mdpi.com/1424-8220/17/12/2762){: target="_blank" rel="noopener noreferrer"}, Yuan et al., 2017

- [Classification of Household Materials via Spectroscopy](https://arxiv.org/abs/1805.04051){: target="_blank" rel="noopener noreferrer"}, Erickson et al., 2018

- [Through-Wall Human Pose Estimation Using Radio Signals](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhao_Through-Wall_Human_Pose_CVPR_2018_paper.pdf){: target="_blank" rel="noopener noreferrer"}, Zhao et al., 2018

- [A bio-hybrid odor-guided autonomous palm-sized air vehicle](https://iopscience.iop.org/article/10.1088/1748-3190/abbd81){: target="_blank" rel="noopener noreferrer"}, Anderson et al., 2020

- [Event-based, Direct Camera Tracking from a Photometric 3D Map using Nonlinear Optimization](https://rpg.ifi.uzh.ch/docs/ICRA19_Bryner.pdf){: target="_blank" rel="noopener noreferrer"}, Bryner et al., 2019

- [SoundSpaces: Audio-Visual Navigation in 3D Environments](https://arxiv.org/abs/1912.11474){: target="_blank" rel="noopener noreferrer"}, Chen et al., 2019

- [Neural Implicit Surface Reconstruction using Imaging Sonar](https://arxiv.org/abs/2209.08221){: target="_blank" rel="noopener noreferrer"}, Qadri et al., 2022


# More Frontiers

### Interpreting Deep Learning Models

- [Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps](https://arxiv.org/abs/1312.6034){: target="_blank" rel="noopener noreferrer"}, Simonyan et al., 2013

- [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391){: target="_blank" rel="noopener noreferrer"}, Selvaraju et al., 2016

- [The Building Blocks of Interpretability](https://distill.pub/2018/building-blocks/){: target="_blank" rel="noopener noreferrer"}, Olah et al., 2018

- [Multimodal Neurons in Artificial Neural Networks](https://distill.pub/2021/multimodal-neurons/){: target="_blank" rel="noopener noreferrer"}, Goh et al., 2021


### Fairness and Ethics

- [Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification](https://proceedings.mlr.press/v81/buolamwini18a.html?mod=article_inline){:target="_blank"}, Buolamwini and Gebru, 2018

- [Saving Face: Investigating the Ethical Concerns of Facial Recognition Auditing](https://dl.acm.org/doi/abs/10.1145/3375627.3375820){:target="_blank"}, Raji et al., 2020


### Articulated Objects

- [Autonomous Tool Construction Using Part Shape and Attachment Prediction](http://www.roboticsproceedings.org/rss15/p09.pdf){: target="_blank" rel="noopener noreferrer"}, Nair et al., 2019

- [Parts-Based Articulated Object Localization in Clutter Using Belief Propagation](https://arxiv.org/abs/2008.02881){: target="_blank" rel="noopener noreferrer"}, Pavlasek et al., 2020

- [Category-Level Articulated Object Pose Estimation](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Category-Level_Articulated_Object_Pose_Estimation_CVPR_2020_paper.html){: target="_blank" rel="noopener noreferrer"}, Li et al., 2020

- [Differentiable Nonparametric Belief Propagation](https://arxiv.org/abs/2101.05948){: target="_blank" rel="noopener noreferrer"}, Opipari et al., 2021

- [Category-Independent Articulated Object Tracking with Factor Graphs](https://arxiv.org/abs/2205.03721){: target="_blank" rel="noopener noreferrer"}, Heppert et al., 2022

- [Kineverse: A Symbolic Articulation Model Framework for Model-Agnostic Mobile Manipulation](https://arxiv.org/abs/2012.05362){: target="_blank" rel="noopener noreferrer"}, Röfer et al., 2022


### Deformable Objects

- [DensePose: Dense Human Pose Estimation In The Wild](https://arxiv.org/abs/1802.00434){: target="_blank" rel="noopener noreferrer"}, Xiao et al., 2018

- [FabricFlowNet: Bimanual Cloth Manipulation with a Flow-based Policy](https://arxiv.org/abs/2111.05623){: target="_blank" rel="noopener noreferrer"}, Weng et al., 2021

- [DextAIRity: Deformable Manipulation Can be a Breeze](https://arxiv.org/abs/2203.01197){: target="_blank" rel="noopener noreferrer"}, Xu et al., 2022

- [Self-supervised Transparent Liquid Segmentation for Robotic Pouring](https://arxiv.org/abs/2203.01538){: target="_blank" rel="noopener noreferrer"}, Narasimhan et al., 2022

- [Visio-tactile Implicit Representations of Deformable Objects](https://arxiv.org/abs/2202.00868){: target="_blank" rel="noopener noreferrer"}, Wi et al., 2022

### Transparent Objects

- [LIT: Light-field Inference of Transparency for Refractive Object Localization](https://arxiv.org/abs/1910.00721){:target="_blank"}, Zhou et al., 2019

- [Multi-modal Transfer Learning for Grasping Transparent and Specular Objects](https://arxiv.org/abs/2006.00028){: target="_blank" rel="noopener noreferrer"}, Weng et al., 2020

- [Dex-NeRF: Using a Neural Radiance Field to Grasp Transparent Objects](https://arxiv.org/abs/2110.14217){:target="_blank"}, Ichnowski et al., 2021

- [ClearPose: Large-scale Transparent Object Dataset and Benchmark](https://arxiv.org/abs/2203.03890){:target="_blank"}, Chen et al., 2022

- [TransNet: Category-Level Transparent Object Pose Estimation](https://arxiv.org/abs/2208.10002){:target="_blank"}, Zhang et al., 2022



### Dynamic Scenes

- [D-NeRF: Neural Radiance Fields for Dynamic Scenes](https://arxiv.org/abs/2011.13961){: target="_blank" rel="noopener noreferrer"}, Pumarola et al., 2020

- [3D Neural Scene Representations for Visuomotor Control](https://arxiv.org/abs/2107.04004){: target="_blank" rel="noopener noreferrer"}, Li et al., 2021

- [HexPlane: A Fast Representation for Dynamic Scenes](https://arxiv.org/abs/2301.09632){: target="_blank" rel="noopener noreferrer"}, Cao and Johnson, 2023



### Beyond 2D Convolutions

- [Learning Decentralized Controllers for Robot Swarms with Graph Neural Networks](https://arxiv.org/abs/1903.10527){: target="_blank" rel="noopener noreferrer"}, Tolstaya et al., 2019

- [A Gentle Introduction to Graph Neural Networks](https://distill.pub/2021/gnn-intro/){: target="_blank" rel="noopener noreferrer"}, Sanchez-Lengeling et al., 2021


### Reinforcement Learning

- [Deep Reinforcement Learning from Human Preferences](https://proceedings.neurips.cc/paper_files/paper/2017/file/d5e2c0adad503c91f91df240d0cd4e49-Paper.pdf){: target="_blank" rel="noopener noreferrer"}, Christiano et al., 2017

- [Understanding RL Vision](https://distill.pub/2020/understanding-rl-vision/){: target="_blank" rel="noopener noreferrer"}, Hilton et al., 2020


### Generative Modeling

- [WaterGAN: Unsupervised Generative Network to Enable Real-time Color Correction of Monocular Underwater Images](https://arxiv.org/abs/1702.07392){: target="_blank" rel="noopener noreferrer"}, Li et al., 2017

- [Differentiable Particle Filters through Conditional Normalizing Flow](https://arxiv.org/abs/2107.00488){: target="_blank" rel="noopener noreferrer"}, Chen et al., 2021

- [Planning with Diffusion for Flexible Behavior Synthesis](https://arxiv.org/abs/2205.09991){: target="_blank" rel="noopener noreferrer"}, Janner et al., 2022

- [Anything-3D: Towards Single-view Anything Reconstruction in the Wild](https://arxiv.org/abs/2304.10261){: target="_blank" rel="noopener noreferrer"}, Shen et al., 2023


