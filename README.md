
# Awesome 3D Human Resources List [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of papers & resources linked to 3D Human research including face, body reconstruction, motion synthesis, etc.

## Contents

- [Tutorials](#tutorials)

- [Papers](#papers)
	- [Face Reconstruction](#papers-slam)
	- [Body Reconstruction](#papers-sfm)

		- [Incremental SfM](#papers-sfm-incremental)
		- [Non Rigid SfM](#papers-non-rigid-sfm)
<br/><br/>
		- [Viewing graph optimization](#papers-sfm-graph)
	- [Hand Reconstruction](#papers-sfm)
	- [Motion Synthesis](#papers-sfm)

- [OpenSource software resources](#opensource)
	- [SfM](#opensource-sfm)

- [Contributing](#contributing)

<a name="tutorials"></a>
# Tutorials

## Tutorial & survey


[Visual Odometry: Part I - The First 30 Years and Fundamentals](http://rpg.ifi.uzh.ch/docs/VO_Part_I_Scaramuzza.pdf), D. Scaramuzza and F. Fraundorfer, IEEE Robotics and Automation Magazine, Volume 18, issue 4, 2011

## RGB-D mapping
[3D indoor scene modeling from RGB-D data: a survey](http://cg.cs.tsinghua.edu.cn/papers/CVMJ-2015-scene-moddeling.pdf) K. Chen, YK. Lai and SM. Hu. Computational Visual Media 2015.


<a name="papers"></a>
# Papers

<a name="face-rec"></a>
## Face Reconstruction
[High-Quality Face Capture Using Anatomical Muscles](http://openaccess.thecvf.com/content_CVPR_2019/papers/Bao_High-Quality_Face_Capture_Using_Anatomical_Muscles_CVPR_2019_paper.pdf). Michael Bao, Matthew Cong, Stephane Grabli, Ronald Fedkiw. CVPR 2019. 
[FML: Face Model Learning From Videos](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tewari_FML_Face_Model_Learning_From_Videos_CVPR_2019_paper.pdf). Ayush Tewari, Florian Bernard, Pablo Garrido, Gaurav Bharaj, Mohamed Elgharib, Hans-Peter Seidel, Patrick Perez, Michael Zollhofer, Christian Theobalt. CVPR 2019.
[Learning to Regress 3D Face Shape and Expression from an Image without 3D Supervision](http://openaccess.thecvf.com/content_CVPR_2019/papers/Sanyal_Learning_to_Regress_3D_Face_Shape_and_Expression_From_an_CVPR_2019_paper.pdf). Soubhik Sanyal, Timo Bolkart, Haiwen Feng, Michael J. Black. CVPR 2019.
[Expressive Body Capture: 3D Hands, Face, and Body From a Single Image](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pavlakos_Expressive_Body_Capture_3D_Hands_Face_and_Body_From_a_CVPR_2019_paper.pdf). Georgios Pavlakos, Vasileios Choutas, Nima Ghorbani, Timo Bolkart, Ahmed A. A. Osman, Dimitrios Tzionas, Michael J. Black. CVPR 2019.
[MVF-Net: Multi-View 3D Face Morphable Model Regression](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wu_MVF-Net_Multi-View_3D_Face_Morphable_Model_Regression_CVPR_2019_paper.pdf). Fanzi Wu, Linchao Bao, Yajing Chen, Yonggen Ling, Yibing Song, Songnan Li, King Ngi Ngan, Wei Liu. CVPR 2019.
[Dense 3D Face Decoding Over 2500FPS: Joint Texture & Shape Convolutional Mesh Decoders](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_Dense_3D_Face_Decoding_Over_2500FPS_Joint_Texture__Shape_CVPR_2019_paper.pdf). Yuxiang Zhou, Jiankang Deng, Irene Kotsia, Stefanos Zafeiriou. CVPR 2019.
[Towards High-Fidelity Nonlinear 3D Face Morphable Model](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tran_Towards_High-Fidelity_Nonlinear_3D_Face_Morphable_Model_CVPR_2019_paper.pdf). Luan Tran, Feng Liu, Xiaoming Liu. CVPR 2019.
[GANFIT: Generative Adversarial Network Fitting for High Fidelity 3D Face Reconstruction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gecer_GANFIT_Generative_Adversarial_Network_Fitting_for_High_Fidelity_3D_Face_CVPR_2019_paper.pdf). Baris Gecer, Stylianos Ploumpis, Irene Kotsia, Stefanos Zafeiriou. CVPR 2019.
[Capture, Learning, and Synthesis of 3D Speaking Styles](http://openaccess.thecvf.com/content_CVPR_2019/papers/Cudeiro_Capture_Learning_and_Synthesis_of_3D_Speaking_Styles_CVPR_2019_paper.pdf). Daniel Cudeiro, Timo Bolkart, Cassidy Laidlaw, Anurag Ranjan, Michael J. Black. CVPR 2019.

Hand
[Learning Joint Reconstruction of Hands and Manipulated Objects](http://openaccess.thecvf.com/content_CVPR_2019/papers/Hasson_Learning_Joint_Reconstruction_of_Hands_and_Manipulated_Objects_CVPR_2019_paper.pdf). Yana Hasson, Gul Varol, Dimitrios Tzionas, Igor Kalevatykh, Michael J. Black, Ivan Laptev, Cordelia Schmid. CVPR 2019.

3D Human Pose Estimation
[3D Human Pose Estimation in Video With Temporal Convolutions and Semi-Supervised Training](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pavllo_3D_Human_Pose_Estimation_in_Video_With_Temporal_Convolutions_and_CVPR_2019_paper.pdf). Dario Pavllo, Christoph Feichtenhofer, David Grangier, Michael Auli. CVPR 2019.
[RepNet: Weakly Supervised Training of an Adversarial Reprojection Network for 3D Human Pose Estimation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wandt_RepNet_Weakly_Supervised_Training_of_an_Adversarial_Reprojection_Network_for_CVPR_2019_paper.pdf). Bastian Wandt, Bodo Rosenhahn. CVPR 2019.
[Generating Multiple Hypotheses for 3D Human Pose Estimation With Mixture Density Network](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Generating_Multiple_Hypotheses_for_3D_Human_Pose_Estimation_With_Mixture_CVPR_2019_paper.pdf). Chen Li, Gim Hee Lee. CVPR 2019.
[Weakly-Supervised Discovery of Geometry-Aware Representation for 3D Human Pose Estimation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Weakly-Supervised_Discovery_of_Geometry-Aware_Representation_for_3D_Human_Pose_Estimation_CVPR_2019_paper.pdf). Xipeng Chen, Kwan-Yee Lin, Wentao Liu, Chen Qian, Liang Lin. CVPR 2019.
[Self-Supervised Learning of 3D Human Pose Using Multi-View Geometry](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kocabas_Self-Supervised_Learning_of_3D_Human_Pose_Using_Multi-View_Geometry_CVPR_2019_paper.pdf). Muhammed Kocabas, Salih Karagoz, Emre Akbas. CVPR 2019.
[Exploiting Temporal Context for 3D Human Pose Estimation in the Wild](http://openaccess.thecvf.com/content_CVPR_2019/papers/Arnab_Exploiting_Temporal_Context_for_3D_Human_Pose_Estimation_in_the_CVPR_2019_paper.pdf). Anurag Arnab, Carl Doersch, Andrew Zisserman. CVPR 2019.
[Semantic Graph Convolutional Networks for 3D Human Pose Regression](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_Semantic_Graph_Convolutional_Networks_for_3D_Human_Pose_Regression_CVPR_2019_paper.pdf). Long Zhao, Xi Peng, Yu Tian, Mubbasir Kapadia, Dimitris N. Metaxas. CVPR 2019.
[3D Human Pose Estimation in Video With Temporal Convolutions and Semi-Supervised Training](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pavllo_3D_Human_Pose_Estimation_in_Video_With_Temporal_Convolutions_and_CVPR_2019_paper.pdf). Dario Pavllo, Christoph Feichtenhofer, David Grangier, Michael Auli. CVPR 2019.


3D Hand Pose Estimation
[Pushing the Envelope for RGB-Based Dense 3D Hand Pose Estimation via Neural Rendering](http://openaccess.thecvf.com/content_CVPR_2019/papers/Baek_Pushing_the_Envelope_for_RGB-Based_Dense_3D_Hand_Pose_Estimation_CVPR_2019_paper.pdf). Seungryul Baek, Kwang In Kim, Tae-Kyun Kim. CVPR 2019.
[Self-Supervised 3D Hand Pose Estimation Through Training by Fitting](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wan_Self-Supervised_3D_Hand_Pose_Estimation_Through_Training_by_Fitting_CVPR_2019_paper.pdf). Chengde Wan, Thomas Probst, Luc Van Gool, Angela Yao. CVPR 2019.


Hand Shape Estimation
[3D Hand Shape and Pose Estimation From a Single RGB Image](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ge_3D_Hand_Shape_and_Pose_Estimation_From_a_Single_RGB_CVPR_2019_paper.pdf). Liuhao Ge, Zhou Ren, Yuncheng Li, Zehao Xue, Yingying Wang, Jianfei Cai, Junsong Yuan. CVPR 2019.
[3D Hand Shape and Pose From Images in the Wild](http://openaccess.thecvf.com/content_CVPR_2019/papers/Boukhayma_3D_Hand_Shape_and_Pose_From_Images_in_the_Wild_CVPR_2019_paper.pdf). Adnane Boukhayma, Rodrigo de Bem, Philip H.S. Torr. CVPR 2019.


Human Capture


[Volumetric Capture of Humans With a Single RGBD Camera via Semi-Parametric Learning](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pandey_Volumetric_Capture_of_Humans_With_a_Single_RGBD_Camera_via_CVPR_2019_paper.pdf). Rohit Pandey, Anastasia Tkach, Shuoran Yang, Pavel Pidlypenskyi, Jonathan Taylor, Ricardo Martin-Brualla, Andrea Tagliasacchi, George Papandreou, Philip Davidson, Cem Keskin, Shahram Izadi, Sean Fanello. CVPR 2019.
[SimulCap : Single-View Human Performance Capture With Cloth Simulation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_SimulCap__Single-View_Human_Performance_Capture_With_Cloth_Simulation_CVPR_2019_paper.pdf). Tao Yu, Zerong Zheng, Yuan Zhong, Jianhui Zhao, Qionghai Dai, Gerard Pons-Moll, Yebin Liu. CVPR 2019.
[Monocular Total Capture: Posing Face, Body, and Hands in the Wild](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xiang_Monocular_Total_Capture_Posing_Face_Body_and_Hands_in_the_CVPR_2019_paper.pdf). Donglai Xiang, Hanbyul Joo, Yaser Sheikh. CVPR 2019.
 
Motion Prediction
[Towards Natural and Accurate Future Motion Prediction of Humans and Animals](http://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Towards_Natural_and_Accurate_Future_Motion_Prediction_of_Humans_and_CVPR_2019_paper.pdf). Zhenguang Liu, Shuang Wu, Shuyuan Jin, Qi Liu, Shijian Lu, Roger Zimmermann, Li Cheng. CVPR 2019.
[A Neural Temporal Model for Human Motion Prediction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gopalakrishnan_A_Neural_Temporal_Model_for_Human_Motion_Prediction_CVPR_2019_paper.pdf). Anand Gopalakrishnan, Ankur Mali, Dan Kifer, Lee Giles, Alexander G. Ororbia. CVPR 2019.
[Learning 3D Human Dynamics From Video](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kanazawa_Learning_3D_Human_Dynamics_From_Video_CVPR_2019_paper.pdf). Angjoo Kanazawa, Jason Y. Zhang, Panna Felsen, Jitendra Malik. CVPR 2019.

Motion Capture
[Neural Scene Decomposition for Multi-Person Motion Capture](http://openaccess.thecvf.com/content_CVPR_2019/papers/Rhodin_Neural_Scene_Decomposition_for_Multi-Person_Motion_Capture_CVPR_2019_paper.pdf). Helge Rhodin, Victor Constantin, Isinsu Katircioglu, Mathieu Salzmann, Pascal Fua. CVPR 2019.


Human Reconstruction
[HoloPose: Holistic 3D Human Reconstruction In-The-Wild](http://openaccess.thecvf.com/content_CVPR_2019/papers/Guler_HoloPose_Holistic_3D_Human_Reconstruction_In-The-Wild_CVPR_2019_paper.pdf). Riza Alp Guler, Iasonas Kokkinos. CVPR 2019.
[Detailed Human Shape Estimation From a Single Image by Hierarchical Mesh Deformation](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhu_Detailed_Human_Shape_Estimation_From_a_Single_Image_by_Hierarchical_CVPR_2019_paper.pdf). Hao Zhu, Xinxin Zuo, Sen Wang, Xun Cao, Ruigang Yang. CVPR 2019.
[Convolutional Mesh Regression for Single-Image Human Shape Reconstruction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kolotouros_Convolutional_Mesh_Regression_for_Single-Image_Human_Shape_Reconstruction_CVPR_2019_paper.pdf). Nikos Kolotouros, Georgios Pavlakos, Kostas Daniilidis. CVPR 2019.
[IGE-Net: Inverse Graphics Energy Networks for Human Pose Estimation and Single-View Reconstruction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jack_IGE-Net_Inverse_Graphics_Energy_Networks_for_Human_Pose_Estimation_and_CVPR_2019_paper.pdf). Dominic Jack, Frederic Maire, Sareh Shirazi, Anders Eriksson. CVPR 2019.
[Learning to Reconstruct People in Clothing From a Single RGB Camera](http://openaccess.thecvf.com/content_CVPR_2019/papers/Alldieck_Learning_to_Reconstruct_People_in_Clothing_From_a_Single_RGB_CVPR_2019_paper.pdf). Thiemo Alldieck, Marcus Magnor, Bharat Lal Bhatnagar, Christian Theobalt, Gerard Pons-Moll. CVPR 2019.



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
