# Self-Driving_Cars_Notebook

![logo](pic/logo.png)

It's a notebook of Self-Driving Cars which is instructed by Prof. Dr.-Ing. Andreas Geiger in 2021.

Class link: [youtube](https://www.youtube.com/playlist?list=PL05umP7R6ij321zzKXK6XCQXAaaYjQbzr).

[Course Website](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/self-driving-cars/) with Slides, Lecture Notes, Problems and Solutions.

![2022-03-14_22-44](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-44.png)

![2022-03-14_22-43](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-43.png)

## L1 Introduction

### 1.1 Organization

![2022-03-14_22-45](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-45.png)

![2022-03-14_22-46](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-46.png)

![2022-03-14_22-46_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-46_1.png)

**https://gym.openai.com/envs/CarRacing-v0/**

![2022-03-14_22-46_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-46_2.png)

![2022-03-14_22-47](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-47.png)

![2022-03-14_22-47_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-47_1.png)

![2022-03-14_22-47_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-47_2.png)

![2022-03-14_22-47_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-47_3.png)

#### Course Materials

- Literature: (links to papers in footnote
  - Janai et al.: Computer Vision for Autonomous Vehicles
    https://arxiv.org/abs/1704.05519
  - Szeliski: Computer Vision: Algorithms and Applications
    https://szeliski.org/Book/
  - Goodfellow, Bengio, Courville: Deep Learning
    http://www.deeplearningbook.org
- Talks, Courses and Tutorials:
  - Stachniss (Bonn): Self-Driving Cars
    https://www.ipb.uni-bonn.de/sdc-2020/
  - Karpathy (Tesla): Tesla AI Day
    https://www.youtube.com/watch?v=j0z4FweCy4M
  - Fridman (MIT): Self-Driving Cars
    https://deeplearning.mit.edu/
  - Urtasun (UoT): All about SD
    http://www.allaboutselfdriving.com/
  - The Python Tutorial
    https://docs.python.org/3/tutorial/
  - NumPy Quickstart
    https://numpy.org/devdocs/user/quickstart.html
  - PyTorch Tutorial
    https://pytorch.org/tutorials/
  - Latex / Overleaf Tutorial
    https://www.overleaf.com/learn

#### Prerequisites

- Basic math skills

  - Linear algebra, probability and information theory. If unsure, have a look at:
    Goodfellow et al.: [Deep Learning (Book)](https://www.deeplearningbook.org/), Chapters 1-4
    Luxburg: [Mathematics for Machine Learning (Lecture)](http://www.tml.cs.uni-tuebingen.de/teaching/2020_maths_for_ml/index.php)
    Deisenroth et al.: Mathematics for Machine Learning (Book)

    ![2022-03-14_22-53](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-53.png)

    ![2022-03-14_22-53_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-53_1.png)

- Basic computer science skills

  - Variables, functions, loops, classes, algorithms

- Experience with deep learning. If unsure, take a deep learning course:

  - Geiger: [Deep Learning (Lecture)](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/deep-learning/)
  - Basic Python and PyTorch coding skills
    https://docs.python.org/3/tutorial/
    https://pytorch.org/tutorials/

### 1.2 Introduction

#### Why Self-Driving Cars?

![2022-03-14_22-56](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-56.png)

![2022-03-14_22-56_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-56_1.png)

![2022-03-14_22-56_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-56_2.png)

![2022-03-14_22-56_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-56_3.png)

![2022-03-14_22-56_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-56_4.png)

![2022-03-14_22-56_5](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-56_5.png)

![2022-03-14_22-57](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-57.png)

![2022-03-14_22-57_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-57_1.png)

### 1.3 History of Self-Driving

#### The Automobile

![2022-03-14_22-58](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-58.png)

![2022-03-14_22-58_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-58_1.png)

![2022-03-14_22-58_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-58_2.png)

#### Self-Driving Cars

![2022-03-14_22-59](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-59.png)

![2022-03-14_22-59_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-59_1.png)

![2022-03-14_22-59_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_22-59_2.png)

![2022-03-14_23-00](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-00.png)

![2022-03-14_23-00_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-00_1.png)

![2022-03-14_23-00_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-00_2.png)

![2022-03-14_23-00_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-00_3.png)

![2022-03-14_23-00_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-00_4.png)

![2022-03-14_23-01](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-01.png)

![2022-03-14_23-01_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-01_1.png)

![2022-03-14_23-01_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-01_2.png)

![2022-03-14_23-01_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-01_3.png)

![2022-03-14_23-01_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-01_4.png)

![2022-03-14_23-01_5](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-01_5.png)

![2022-03-14_23-02](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-02.png)

![2022-03-14_23-02_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-02_1.png)

![2022-03-14_23-02_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-02_2.png)

![2022-03-14_23-02_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-02_3.png)

![2022-03-14_23-03](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-03.png)

![2022-03-14_23-03_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-03_1.png)

![2022-03-14_23-03_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-03_2.png)

![2022-03-14_23-04](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-04.png)

![2022-03-14_23-04_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-04_1.png)

![2022-03-14_23-04_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-04_2.png)

![2022-03-14_23-04_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-04_3.png)

![2022-03-14_23-04_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-04_4.png)

![2022-03-14_23-05](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-05.png)

![2022-03-14_23-05_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-05_1.png)

![2022-03-14_23-05_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-05_2.png)

![2022-03-14_23-05_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-05_3.png)

![2022-03-14_23-05_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-05_4.png)

![2022-03-14_23-06](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-06.png)

![2022-03-14_23-06_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-06_1.png)

![2022-03-14_23-06_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-06_2.png)

![2022-03-14_23-06_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-06_3.png)

![2022-03-14_23-06_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-06_4.png)

![2022-03-14_23-06_5](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-06_5.png)

![2022-03-14_23-07](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07.png)

![2022-03-14_23-07_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07_1.png)

![2022-03-14_23-07_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07_2.png)

![2022-03-14_23-07_3](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07_3.png)

![2022-03-14_23-07_4](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07_4.png)

![2022-03-14_23-07_5](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07_5.png)

![2022-03-14_23-07_6](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-07_6.png)

![2022-03-14_23-08](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-08.png)

![2022-03-14_23-08_1](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-08_1.png)

![2022-03-14_23-08_2](/home/wenboji/Self-Driving_Cars_Notebook/pic/2022-03-14_23-08_2.png)

## L2 Imitation Learning

### 2.1 Approaches to Self-Driving

### 2.2 Deep Learning Recap

### 2.3 Imitation Learning

### 2.4 Conditional Imitation Learning

## L3 Direct Perception

### 3.1 Direct Perception

### 3.2 Conditional Affordance Learning

### 3.3 Visual Abstractions

### 3.4 Driving Policy Transfer

### 3.5 Online vs. Offline Evaluation

## L4 Reinforcement Learning

### 4.1 Markov Decision Processes

### 4.2 Bellman Optimality and Q-Learning

### 4.3 Deep Q-Learning

## L5 Vehicle Dynamics

### 5.1 Introduction

### 5.2 Kinematic Bicycle Model

### 5.3 Tire Models

### 5.4 Dynamic Bicycle Model

## L6 Vehicle Control

### 6.1 Introduction

### 6.2 Black Box Control

### 6.3 Geometric Control

### 6.4 Optimal Control

## L7 Odometry, SLAM and Localization

### 7.1 Visual Odometry

### 7.2 Simultaneous Localization and Mapping

### 7.3 Localization 

## L8 Road and Lane Detection

### 8.1 Introduction

### 8.2 Road Segmentation

### 8.3 Lane Marking Detection

### 8.4 Lane Detection

### 8.5 Lane Tracking

## L9 Reconstruction and Motion

### 9.1 Stereo Matching

### 9.2 Freespace and Stixels

### 9.3 Optical Flow

### 9.4 Scene Flow

## L10 Object Detection

### 10.1 Introduction

### 10.2 Performance Evaluation

### 10.3 Sliding Window Object Detection

### 10.4 Region Based CNNs

### 10.5 3D Object Detection

## L11 Object Tracking

### 11.1 Introduction

### 11.2 Filtering

### 11.3 Association

### 11.4 Holistic Scene Understanding

## L12 Decision Making and Planning

### 12.1 Introduction

### 12.2 Route Planning

### 12.3 Behavior Planning

### 12.4 Motion Planning