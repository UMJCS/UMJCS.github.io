---
title: "Resume"
permalink: /resume/
author_profile: true
toc: true
toc_label: "Quick Guide"
toc_icon: "cog"
toc_sticky: true
classes: wide

feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."


feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"


feature_row3:
  - image_path: /assets/img/moment/iccv19/LGAN.png
    alt: "LGAN"
    excerpt: 'Pipeline of Liquid Warping GAN'


feature_row4:
  - image_path: /assets/img/moment/undergraduate/VCIP.png
    alt: "DAVid GAN"
    excerpt: 'Pipeline of DAVid GAN'

ppo:
  - url: /assets/img/moment/project/ppo2.png
    image_path: assets/img/moment/project/ppo2.png
    alt: "New Cliping Function"

  - url: /assets/img/moment/project/ppo1.png
    image_path: assets/img/moment/project/ppo1.png
    alt: "More Adaptive Memory Management Methods, similar to LSTM"

  - url: /assets/img/moment/project/ppo3.png
    image_path: assets/img/moment/project/ppo3.png
    alt: "Reward Curves"

david:
  - url: /assets/img/moment/undergraduate/VCIP.png
    image_path: assets/img/moment/undergraduate/VCIP.png
    alt: "DAvid GAN"

---


## Education
### **University of Pennsylvania**  
*Master of Science in Engineering, Robotics*        |  August 2019 - May 2021 |
***Current GPA: 4.0/4.0***

> **Courses** || Advanced Topic in Explainable AI (A+), Machine Perception(A+), Advanced Topic in Machine Perception (A), BigData (A), Linear/Nonlinear Optimization (A), Deep Learning in Data Sci (A)
> 
> **Research** || Join GRASP Lab, advised by Prof. Jianbo Shi, interested in Computer Vision and Machine Learning. One paper accpeted by CVPR20', Submitted one papers to ECCV20'


### **ShanghaiTech University**
*Bachelor of Computer Science and Engineering*        |  August 2015 - June 2019 |
***Major GAP: 3.75/4.0***

> **Highlighted Courses** || Deep Learning, Computer Vision, Advanced Algorithm, Autonomous Robotics
> 
> **Research Interests** || 3D Human Motion Animation, Unsupervised Learning, Detection/Segmentation
> 
> **Publications** || One paper accepted by ICCV19' (Liquid Warping GAN) [**Website**](https://svip-lab.github.io/project/impersonator.html)


## Skills

**Languages** | python,C++,Pytorch,Tensorflow,JAVA,SQL
**Technologies** | Linux, Multi-GPU Server, Latex, Vim, Git, Arxiv
**Research Interests** | 3D Human Motion Animation, Unsupervised Learning, Detection/Segmentation
**Publications** | One paper accepted ICCV19' (Liquid Warping GAN), One paper accepted CVPR20' (Nested Scale-Editing for Conditional Image Synthesis), One paper under reviewing of ECCV20' (Mental Replay: Learning Diverse Object Placement by Inpainting for Compositional Data Augmentation).

## Selected Experiences

### Publication/Research Intern
* **Liquid-Warping GAN: A Unified Framework for Human Motion Imitation, Appearance Transfer and Novel View Synthesis** *(Accepted by ICCV19')* || *Perception Lab, ShanghaiTech University, Prof. Shenghua Gao* || 11/2018-04/2019 

{% include figure image_path="/assets/img/moment/iccv19/LGAN.png" alt="PipeLine of Liquid Warping GAN" %}

{% include video id="nhla-Mfq2Wc" provider="youtube" %}

> Funny Demos and codes are public on the website: [**Website**](https://svip-lab.github.io/project/impersonator.html), [**Paper**](https://arxiv.org/pdf/1909.12224.pdf), [**Code**](https://github.com/svip-lab/impersonator).
> 
> Estimate pose, shape and camera information using *HMR* framework. And then send arranged info to *SMPL* module, which outputs meticulous 3D mesh and then render back to 2D image.
> To make generation step smoother, we apply transformation of the two input sources not only on pixel level, but also on *autoencoder's feature spaces*. GAN could generate more realistic images and "guess" unseen parts.

{% include video id="LEz0jgTiLyk" provider="youtube" %}

* **Nested Scale-Editing for Conditional Image Synthesis** *(Accpeted by CVPR20')* || *GRASP Lab, University of Pennsylvania, Prof. Jianbo Shi* || 08/2019-11/2019

> ***Details will Updated After the Deadline.***
> 
> We propose an image synthesis approach that provides stratified navigation in the latent code space. With a tiny amount of partial or very low-resolution image, our approach can consistently out-perform state-of-the-art counterparts in terms of generating the closest sampled image to the ground truth. We achieve this through scale-independent editing while expanding scale-specific diversity. Scale-independence is achieved with a nested scale disentanglement loss. Scale-specific diversity is created by incorporating a progressive diversification constraint. We introduce semantic persistency across the scales by sharing common latent codes. Together they provide better control of the image synthesis process. We evaluate the effectiveness of our proposed approach through various tasks, including image outpainting, image superresolution, and cross-domain image translation.



* **Mental Replay: Learning Diverse Object Placement by Inpainting for Compositional Data Augmentation** *(Submitted to ECCV20')* || *GRASP Lab, University of Pennsylvania, Prof. Jianbo Shi* || 08/2019-11/2019

> ***Details will Updated After the Deadline.***
> 
> We study the problem of common sense placement of visual objects in an image. This involves multiple aspects of visual recognition: the instance segmentation of the scene, 3D layout, and common knowledge of how objects are placed and where objects are moving in the 3D scene. This seemingly simple task is difficult for current learning based approaches because of the lack of labeled training data which ideally should consist of a variety of foreground objects paired with cleaned background scenes with no objects with many demonstrated plausible object locations. Because of this challenge, many current solutions only work in synthetic environments or rely on dense supervision. We propose a self-learning framework that automatically generates the necessary training data without any manual labeling by detecting, cutting, and inpainting objects from an image. We learn a generative model that predicts a distribution of common sense locations when given a foreground object and a background scene. We show experimentally our object placement network can be used to augment training data to boost instance segmentation. In addition, the learned representation of our placement network displays strong discriminative power in image retrieval and transfer learning. Inspired by human’s memory system, we call our self-supervised learning system mental replay.


* **DAVid GAN: **D**etect **A**nomalies in **Vid**eo with GAN** *(Submitted to VCIP19' && Bachelor Thesis)* || *Perception Lab, ShanghaiTech University, Prof. Shenghua Gao* || 03/2019-06/2019

> I proposed to learn pattern representation of normal events instead of abnormal, which tackles problems in existing methods and improves average 7.2% AUC among results. 
> 
> The network is composed of two modules: an **Bi-sided Generator** takes optical flow and RGB frames as input, and output reconstruction on the other side; An **LSTM Network** takes sequential human joints info as input, and predicts future motions.

{% include figure image_path="/assets/img/moment/undergraduate/VCIP.png" alt="PipeLine of DAVid GAN" %}

## Selected Projects

* Multimodal Unsupervised "Inverse Style Transfer" on Human Face ***{Deep Learning Course Project}***
* LSTM-PPO: Memory Adaptive PPO and other methods to Reinforcement Learning in Car Racing Task ***{Perception Course Project}*** > [**Report**](https://drive.google.com/file/d/1saw4JXxkzKHziaZH1A96tZzBoH4EwG9a/view?usp=sharing)
{% include gallery id="ppo" caption="Novelty and Improvements of Our LSTM-PPO" %}
* MURA Musculoskeletal Radiographs Bone X-Ray Deep Learning Competition Stanford Machine Learning Group ***{Independent Research Project}***
* Auto-Picking - Protein Particle Recognition and Segmentation in Cryo-electron Microscopy using Regions with CNNs Features (RCNN) ***{Independent Research Project}***
* Training a Sparse-Reward Agent for First-Person Shooter Game using DDRQN and Curriculum Learning ***{Artificial Intelligence Course Project}*** > [**Report**](https://drive.google.com/file/d/1pkwgoHNBH9bqGZ2nSM9DQa2EVF_1WiB6/view?usp=sharing)
{% include video id="1__iQdddc1it2GI75w08Z3DpM1KefMAMb" provider="google-drive" %}
* Using Kinect to Detect Human Skeleton and Gestures Point-To-Point Control AR Game Models to Fight ***{Computer Vision Course Project}*** 
{% include video id="1Iwb_WZKBH9JaNYWicZby67lfDR4g5InF" provider="google-drive" %}
* A Near-Linear Time Algorithm for Computing Replacement Paths in Planar Directed Graphs ***{Advanced Algorithm Course Project}*** > [**Report**](https://drive.google.com/file/d/1p7KBmwg4kMR4J6J2Bg6IYUIDysd_Wird/view?usp=sharing)

## Other Experiences

### RA (Research Assistant)
* Research Assitant at Nanyang Technology University, Singapore, LILY Lab.

### TA (Teaching Assistant)
* Introduction to Computer Science
* Computer Vision
* Data Structure
* Undergraduate Mentor of Math @ Upenn

