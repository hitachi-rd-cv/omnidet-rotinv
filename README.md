Annotations for Omnidirectional Pedestrian Detection
====

This page provides annotations for 4 publicly available datasets,
[Mirror Worlds Challenge](https://icat.vt.edu/mirrorworlds/challenge/index.html),
[PIROPO](https://sites.google.com/site/piropodatabase/),
[Bomni](https://www.cmpe.boun.edu.tr/pilab/pilabfiles/databases/bomni/), and
[CVRG](http://cvrg.iyte.edu.tr/). The annotations are used in our paper,
[Omnidirectional Pedestrian Detection by Rotation Invariant Training](https://ieeexplore.ieee.org/document/8658933).
If you use our annotations, please follow a limitation, and cite our paper.

## Description
In this page, only annotation files are provided. For training and evaluation, please download the original images from
the original websites.

The annotation files for each sequence are placed in the same directory structure as the original, and the annotation file
name is the same name as the original image file except for the extension.
The annotations are provided in XML files that are based on [Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/ "Pascal") format.
All the objects in the annotation files are named as "person".

We provide two types of annotations. One expresses pedestrians' area by horizontal bounding boxes, and the other
expresses them by rotated bounding boxes. The former type of annotations are contained in "normal.tar.gz",
and the latter type of annotations are contained in "rotate.tar.gz". When you use rotated version, you must rotate
bounding boxes by yourself. Rotation angle for each bounding box is the angle between a vertical line and
a line connecting a image center and bounding box center.

## Annotations
### Mirror Worlds challenge
The dataset can be downloaded from [here](http://www2.icat.vt.edu/mirrorworlds/challenge/index.html "MW").

The annotations are placed in "mw_18mar" directory in each tar file. Annotation statistics are as follows:

| Sequence name | #Annotation files | #Instances |
| :--- | ---: | ---: |
| MW-18Mar-1 | 39 | 39 |
| MW-18Mar-2 | 24 | 36 |
| MW-18Mar-3 | 74 | 75 |
| MW-18Mar-4 | 31 | 52 |
| MW-18Mar-5 | 30 | 54 |
| MW-18Mar-6 | 42 | 76 |
| MW-18Mar-7 | 45 | 83 |
| MW-18Mar-8 | 45 | 58 |
| MW-18Mar-9 | 45 | 140 |
| MW-18Mar-10 | 46 | 184 |
| MW-18Mar-11 | 46 | 183 |
| MW-18Mar-12 | 46 | 184 |
| MW-18Mar-13 | 45 | 129 |
| MW-18Mar-14 | 45 | 141 |
| MW-18Mar-15 | 46 | 184 |
| MW-18Mar-16 | 46 | 181 |
| MW-18Mar-17 | 46 | 184 |
| MW-18Mar-18 | 43 | 121 |
| MW-18Mar-19 | 34 | 57 |
| MW-18Mar-20 | 46 | 79 |
| MW-18Mar-21 | 36 | 55 |
| MW-18Mar-22 | 46 | 105 |
| MW-18Mar-23 | 46 | 91 |
| MW-18Mar-24 | 46 | 83 |
| MW-18Mar-25 | 46 | 168 |
| MW-18Mar-26 | 46 | 115 |
| MW-18Mar-27 | 41 | 175 |
| MW-18Mar-28 | 46 | 166 |
| MW-18Mar-29 | 18 | 33 |
| MW-18Mar-30 | 46 | 155 |
| MW-18Mar-31 | 19 | 35 |

### PIROPO
The dataset can be downloaded from [here](https://sites.google.com/site/piropodatabase/ "PIROPO").

The annotations are placed in "piropo" directory in each tar file. Annotation statistics are as follows:

| Sequence name | #Annotation files | #Instances |
| :--- | ---: | ---: |
| Room_A/omni_1A/omni_1A_training | 750 | 750 |
| Room_A/omni_1A/omni_1A_test2 | 119 | 296 |
| Room_A/omni_1A/omni_1A_test3 | 141 | 141 |
| Room_A/omni_2A/omni_2A_test3 | 120 | 120 |
| Room_A/omni_2A/omni_2A_test2 | 113 | 261 |
| Room_A/omni_2A/omni_2A_training | 701 | 727 |
| Room_A/omni_3A/omni_3A_test2 | 116 | 198 |
| Room_A/omni_3A/omni_3A_training | 487 | 487 |
| Room_A/omni_3A/omni_3A_test3 | 65 | 65 |
| Room_B/omni_1B/omni_1B_test2 | 27 | 48 |
| Room_B/omni_1B/omni_1B_training | 419 | 426 |
| Room_B/omni_1B/omni_1B_test3 | 31 | 31 |

### Bomni
The dataset can be downloaded from [here](https://drive.google.com/file/d/1CTrNbzSJ-ZAUhakQAYnc2ZVfPFuH4MKH/view "Bomni").

The original dataset provides videos, so we split them into images. The image file name is determined with four-digit serial number starting from 1.
The annotations are placed in "bomni" directory in each tar file. Annotation statistics are as follows:

| Sequence name | #Annotation files | #Instances |
| :--- | ---: | ---: |
| scenario1/top-1 | 80 | 232 |
| scenario1/top-3 | 91 | 351 |
| scenario1/top-2 | 65 | 251 |
| scenario1/top-0 | 101 | 288 |

### CVRG
The dataset can be downloaded from [here](http://cvrg.iyte.edu.tr/ "CVRG"). The dataset we used is Dataset 1 of 4) Omnidirectional and panoramic image dataset (with annotations) to be used for human and car detection.

The annotations are placed in "cvrg" directory in each tar file. Annotation statistics are as follows:

| Sequence name | #Annotation files | #Instances |
| :--- | ---: | ---: |
| Human Set/omni | 30 | 71 |

## Limitation
All the original datasets are provided for research purpose only.
We provide our annotations following the original limitations.

## Citation
If you use our annotations, please cite [our paper](https://ieeexplore.ieee.org/document/8658933):
```
@inproceedings{masato_wacv2019,
author = {Tamura, Masato and Horiguchi, Shota and Murakami, Tomokazu},
title = {Omnidirectional Pedestrian Detection by Rotation Invariant Training},
booktitle={2019 IEEE Winter Conference on Applications of Computer Vision (WACV)},
year = {2019},
month = {January},
pages = {1989-1998},
}
```
