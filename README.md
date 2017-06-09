# A comprehensive study on upper-body detection with deep learning methods

Yamei Zhu, Lin Zhang

School of Software Engineering, Tongji University, Shanghai, China

---
## Introduction 
This is the website for our paper "A comprehensive study on upper-body detection with deep learning methods", submitted to **ICONIP 2017**. 

The pedestrian detection task is of paramount importance for many real-world applications. However the researchers generally ignore the critical issue that the definition for "pedestrian" is ill-posed in many cases. At the same time, pedestrian detection can be substituted by upper-body detection. It is more robust and is much less affected by occlusion or being partially out of FOV, but few studies have been conducted in this area. Most of the upper-body datasets are acquired from TV shows for motion classification or action recognition.The viewpoints of these datasets are similar and the backgrounds are simple. The numbers of the people in the images are limited, usually 2 to 3 people. As a result, these datasets are not suitable to detect the upper-body areas of pedestrians. For applications in ADAS or surveillance, the scenes need to be on the road with a lot of people, with low image resolution and high view-point. In surveillance videos, the crowd may cause occlusion in the videos. Some researchers use INRIA Person Dataset to train upper-body detectors. But as INRIA Person Dataset only contain annotated pedestrians, researchers have to refine the dataset by themselves. So the exist datasets are not enough for upper-body detection. We establish a large-scale benchmark dataset for upper-body detection. This dataset comprises 9585 images extracted from typical surveillance video clips.

## Upper-body Dataset 1.0

We have established a large-scale benchmark dataset for upper-body detection.

1. Upper-body Image Set([JPEGImages](https://nodejs.org/))
 Unzip RAR files, "JPEGImages.rar". there are 9585 images extracted from typical surveillance video clips.
2. Annotations ([Annotations.rar]())
Unzip RAR files, "Annotations.rar". This folder have ever corrispond annotations to the upper-body image set. The upper-body regions were cropped very carefully for each image.

