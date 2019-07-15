
# Awesome 3D Human Resources List [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of papers & resources linked to 3D Human including face, body reconstruction, motion synthesis, etc.

## Contents

- [Tutorials](#tutorials)

- [Papers](#papers)
	- [SLAM](#papers-slam)
	- [SFM](#papers-sfm)

		- [Incremental SfM](#papers-sfm-incremental)
		- [Global SfM](#papers-sfm-global)
		- [Hierarchical SfM](#papers-sfm-hierarchical)
		- [Multi-Stage SfM](#papers-sfm-multi-stage)
		- [Non Rigid SfM](#papers-non-rigid-sfm)
<br/><br/>
		- [Viewing graph optimization](#papers-sfm-graph)
		- [Unordered feature tracking](#papers-sfm-tracking)
		- [Large scale image matching for SfM](#papers-sfm-large-scale-matching)

- [OpenSource software resources](#opensource)
	- [SfM](#opensource-sfm)
	- [Multiple View Geometry Library Solvers](#opensource-solvers)
	- [MVS (Multiple View Stereovision)](#opensource-mvs)
	- [SLAM](#opensource-slam)
	- [Large Scale Image Retrieval](#opensource-cbir)
	- [Minimization](#opensource-minimization)
	- [Nearest Neighbor Search](#opensource-nn)
	- [Mesh storage processing](#opensource-mesh)

- [License](#license)

- [Contributing](#contributing)

<a name="tutorials"></a>
# Tutorials

## Tutorial & survey


[Visual Odometry: Part I - The First 30 Years and Fundamentals](http://rpg.ifi.uzh.ch/docs/VO_Part_I_Scaramuzza.pdf), D. Scaramuzza and F. Fraundorfer, IEEE Robotics and Automation Magazine, Volume 18, issue 4, 2011

## RGB-D mapping
[3D indoor scene modeling from RGB-D data: a survey](http://cg.cs.tsinghua.edu.cn/papers/CVMJ-2015-scene-moddeling.pdf) K. Chen, YK. Lai and SM. Hu. Computational Visual Media 2015.


<a name="papers"></a>
# Papers

<a name="papers-slam"></a>
## SLAM/VO

### Visual odometry (image based only)

[Real-time simultaneous localisation and mapping with a single camera](https://www.doc.ic.ac.uk/~ajd/Publications/davison_iccv2003.pdf). A. J. Davison. ICCV 2003.

<a name="papers-sfm"></a>
## SfM papers

<a name="papers-sfm-incremental"></a>
### Incremental SfM
[Photo Tourism: Exploring Photo Collections in 3D](http://phototour.cs.washington.edu/Photo_Tourism.pdf). N. Snavely, S. M. Seitz, and R. Szeliski.  SIGGRAPH 2006.


<a name="papers-sfm-hierarchical"></a>
### Hierarchical SfM
[Structure-and-Motion Pipeline on a Hierarchical Cluster Tree](http://www.diegm.uniud.it/fusiello/papers/3dim09.pdf).  A. M.Farenzena, A.Fusiello, R. Gherardi. Workshop on 3-D Digital Imaging and Modeling, 2009.



<a name="opensource-solvers"></a>
## OpenSource Multiple View Geometry Library Solvers

| Project |  Language | License |
| ---  | --- | --- |
|[OpenGV](https://github.com/laurentkneip/opengv) | C++ | BSD - permissive |


<a name="opensource-slam"></a>
## OpenSource SLAM (Simultaneous Localization And Mapping)

| Project |  Language | License |
| ---  | --- | --- |
|[COSLAM](http://drone.sjtu.edu.cn/dpzou/project/coslam.php) | C++ |  GNU General Public License|
|[DSO-Direct Sparse Odometry](https://github.com/JakobEngel/dso) | C++ |  GPLv3|
|[DTSLAM-Deferred Triangulation SLAM](https://github.com/plumonito/dtslam) | C++ |  modified BSD|
|[LSD-SLAM](https://github.com/tum-vision/lsd_slam/) | C++/ROS |  GNU General Public License|
|[MAPLAB-ROVIOLI](https://github.com/ethz-asl/maplab) | C++/ROS |  Apachev2.0|

# Contributing
Please see [CONTRIBUTING](https://github.com/openMVG/awesome_3DReconstruction_list/blob/master/contributing.md) for details.
