# My Project Plan 

***Note :*** This document is written merely as an illustrative example, and does not provide ant working guide to an actual project.

### Proposal
---
I am planning to make a computer vision software that detects objects in images.

In order to built it, I will use opencv, deep learning libraries, such as [TensorFlow](https://www.tensorflow.org/?hl=ko) or [PyTorch](https://pytorch.org/), and other open source softwares.

For example, the objects in the following images were detected using [mmdetection](https://github.com/open-mmlab/mmdetection):

![이미지](https://github.com/zeewon0123/First/blob/main/137271636-56ba1cd2-b110-4812-8221-b4c120320aa9.png)

### Dependencies
---
+ python
+ opencv-python
+ tensorflow
+ openmmlab
+ package manager

### Installation
---
In a bash terminal, run the following commands ( _Do NOT actually run these command in your computer_ ):

```sh
$ sudo apt update
$ conda create -n cv_detection
$ conda activate cv_detection
$ python --version
$ python example.py
```
