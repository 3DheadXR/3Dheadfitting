# Single-camera 3D head fitting for mixed reality clinical applications

Tejas Mane, Aylar Bayramova, Kostas Daniilidis, Philippos Mordohai, Elena Bernardis
               
University of Pennsylvania and Stevens Institute of Technology

![Image](https://user-images.githubusercontent.com/43998771/157100759-c444c829-101f-4833-8f50-5357351bc15c.jpeg)

### Abstract
We address the problem of estimating the shape of a person’s head, defined as the geometry of the complete head surface, from a video taken with a single moving camera, and determining the alignment of the fitted 3D head for all video frames, irrespective of the person’s pose. 3D head reconstructions commonly tend to focus on perfecting the face reconstruction, leaving the scalp to a statistical approximation. Our goal is to reconstruct the head model of each person to enable future mixed reality applications. To do this, we recover a dense 3D reconstruction and camera information via structure-from-motion and multi-view stereo. These are then used in a new two-stage fitting process to recover the 3D head shape by iteratively fitting a 3D morphable model of the head with the dense reconstruction in canonical space and fitting it to each person’s head, using both traditional facial landmarks and scalp features extracted from the head’s segmentation mask. Our approach recovers consistent geometry for varying head shapes, from videos taken by different people, with different smartphones, and in a variety of environments from living rooms to outdoor spaces.    

[[Download pdf]](https://doi.org/10.1016/j.cviu.2022.103384)
[[ArXiv]](https://arxiv.org/abs/2109.02740) 

### Technical Video

Coming Soon.

### BibTex 

@article{MANE2022103384,
author = {Tejas Mane and Aylar Bayramova and Kostas Daniilidis and Philippos Mordohai and Elena Bernardis},
title = {Single-camera 3D head fitting for mixed reality clinical applications},
journal = {Computer Vision and Image Understanding},
volume = {218},
pages = {103384},
year = {2022},
issn = {1077-3142},
doi = {https://doi.org/10.1016/j.cviu.2022.103384}
}
