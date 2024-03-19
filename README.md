# Awesome LiDAR Place Recognition [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![image](awesome-lidar-place-recognition.gif)

> Thumbnail Figures from Complex Urban, Wild-Places, and DiTer datasets / our place recognition method (TBD) / DiSCo-SLAM.  

This repository is the collection of LiDAR Place Recognition Research that provides a code or a download page, together. This repository also reports the datasets for Place Recognition and various algorithms utilized in Place Recognition (e.g. multi-robot mapping, SLAM).

LiDAR Place Recognition can be broadly categorized into **handcrafted**-based and **learning**-based methods. 

Datasets for LiDAR Place Recognition are classified into **single-session**, **multi-session**, and **multi-robot session**. Additionally, it is possible to confirm which **LiDAR** was used and which **vehicle** was utilized (🚙 🤖 🛩️ 🚢).

Finally, **various algorithms** that play an important role in Place Recognition are introduced.

🔥 represents a paper citation count of 50 or more, or a code's star count of 50 or more.

## News
[24.03.19] First commit! 


## LiDAR Place Recognition Methods

- 2024

  - **'`Handcraft`** **'ICRA'** Effectively Detecting Loop Closures using Point Cloud Density Maps [[pdf](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/gupta2024icra.pdf)] [[code](https://github.com/PRBonn/MapClosures)] 🔥

  - [Handcraft] [❓] BTC: A Binary and Triangle Combined Descriptor for 3D Place Recognition` [under-review] [[code](https://github.com/hku-mars/btc_descriptor)] 🔥

  - [Learning] [RAL] P-GAT : Pose-Graph Attentional Network for Lidar Place Recognition [[pdf](https://arxiv.org/pdf/2309.00168.pdf)] [[code](https://github.com/csiro-robotics/P-GAT)]


- 2023

  - [Handcraft] [TRO] RING++: Roto-Translation-Invariant Gram for Global Localization on a Sparse Scan Map [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10224330)] [[code](https://github.com/lus6-Jenny/RING)] 🔥

  - [Handcraft] [ICRA] STD: A Stable Triangle Descriptor for 3D place recognition [[pdf](https://arxiv.org/pdf/2209.12435.pdf)] [[code](https://github.com/hku-mars/STD)] 🔥
  
  - [Learning] [ICCV] BEVPlace: Learning LiDAR-based Place Recognition using Bird's Eye View Images [[pdf](https://arxiv.org/pdf/2302.14325.pdf)] [[code](https://github.com/zjuluolun/BEVPlace)] 🔥
  
  - [Learning] [IROS] Uncertainty-Aware Lidar Place Recognition in Novel Environments [[pdf](https://arxiv.org/pdf/2210.01361.pdf)] [[code](https://github.com/csiro-robotics/Uncertainty-LPR)] 🔥


- 2022
  
    - [Handcraft] [ICARCV] Frequency-Domain Scan Context for Robust LiDAR-based Place Recognition with Translation and Rotation Invariance [[pdf](https://arxiv.org/pdf/2206.12628.pdf)] [[code](https://github.com/soytony/FreSCo)] 🔥
  
    - [Handcraft] [TRO] Scan Context++: Structural Place Recognition Robust to Rotation and Lateral Variations in Urban Environments [[pdf](https://arxiv.org/pdf/2109.13494.pdf)] [[code](https://github.com/gisbi-kim/scancontext_tro)] 🔥
  
    - [Learning] [ICRA] LoGG3D-Net: Locally Guided Global Descriptor Learning for 3D Place Recognition [[pdf](https://arxiv.org/pdf/2109.08336.pdf)] [[code](https://github.com/csiro-robotics/LoGG3D-Net)] 🔥
  
    - [Learning] [RAL/IROS] OverlapTransformer: An Efficient and Yaw-Angle-Invariant Transformer Network for LiDAR-Based Place Recognition [[pdf](https://arxiv.org/pdf/2203.03397.pdf)] [[code](https://github.com/haomo-ai/OverlapTransformer)] 🔥
  
    - [Learning] [CVPR] BVMatch: Lidar-based Place Recognition Using Bird's-eye View Images [[pdf](https://arxiv.org/pdf/2109.00317.pdf)] [[code](https://github.com/zjuluolun/BVMatch)] 🔥
  
    - [Learning] [RAL] RINet: Efficient 3D Lidar-Based Place Recognition Using Rotation Invariant Neural Network [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9712221)] [[code](https://github.com/lilin-hitcrt/RINet)] 
  
    - [Learning] [TRO] LCDNet: Deep Loop Closure Detection and Point Cloud Registration for LiDAR SLAM [[pdf](https://arxiv.org/pdf/2103.05056.pdf)] [[code](https://github.com/robot-learning-freiburg/LCDNet)] 🔥
  
    - [Learning] [ICPR] Improving Point Cloud Based Place Recognition with Ranking-based Loss and Large Batch Training [[pdf](https://arxiv.org/pdf/2203.00972.pdf)] [[code](https://github.com/jac99/MinkLoc3Dv2)] 🔥
  
    - [Learning] [IROS] InCloud: Incremental Learning for Point Cloud Place Recognition [[pdf](https://arxiv.org/pdf/2203.00807.pdf)] [[code](https://github.com/csiro-robotics/InCloud)]
  
    - [Learning] [TIE] SeqOT: A Spatial-Temporal Transformer Network for Place Recognition Using Sequential LiDAR Data [[pdf](https://arxiv.org/pdf/2209.07951.pdf)] [[code](https://github.com/BIT-MJY/SeqOT)] 🔥


- 2021

    - [Handcraft] [ICRA] Robust Place Recognition using an Imaging Lidar [[pdf](https://arxiv.org/pdf/2103.02111.pdf)] [[code](https://github.com/TixiaoShan/imaging_lidar_place_recognition)] 🔥

    - [Learning] [ICRA] Locus: LiDAR-based Place Recognition using Spatiotemporal Higher-Order Pooling [[pdf](https://arxiv.org/pdf/2011.14497.pdf)] [[code](https://github.com/csiro-robotics/locus)] 🔥

    - [Learning] [ICRA] NDT-Transformer: Large-Scale 3D Point Cloud Localisation using the Normal Distribution Transform Representation [[pdf](https://arxiv.org/pdf/2103.12292.pdf)] [[code](https://github.com/dachengxiaocheng/NDT-Transformer)] 🔥

    - [Learning] [RAL/ICRA] Disco: Differentiable scan context with orientation [[pdf](https://arxiv.org/pdf/2010.10949.pdf)] [[code](https://github.com/MaverickPeter/DiSCO-pytorch)] 🔥

    - [Learning] [RAL] EgoNN: Egocentric Neural Network for Point Cloud Based 6DoF Relocalization at the City Scale [[pdf](https://arxiv.org/pdf/2110.12486.pdf)] [[code](https://github.com/jac99/Egonn)]

    - [Learning] [WACV] MinkLoc3D: Point Cloud Based Large-Scale Place Recognition [[pdf](https://arxiv.org/pdf/2011.04530.pdf)] [[code](https://github.com/jac99/MinkLoc3D)] 🔥

    - [Learning] [RAL] MinkLoc3D-SI: 3D LiDAR Place Recognition With Sparse Convolutions, Spherical Coordinates, and Intensity [[pdf](https://arxiv.org/pdf/2112.06539.pdf)] [[code](https://github.com/KamilZywanowski/MinkLoc3D-SI)]


- 2020

  - [Handcraft] [IROS] LiDAR Iris for Loop-Closure Detection [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9341010)] [[code](https://github.com/BigMoWangying/LiDAR-Iris)] 🔥

  - [Handcraft] [ICRA] Intensity Scan Context: Coding Intensity and Geometry Relations for Loop Closure Detection [[pdf](https://arxiv.org/pdf/2003.05656.pdf)] [[code](https://github.com/wh200720041/iscloam)] 🔥

  - [Learning] [RSS] OverlapNet: Loop Closing for LiDAR-based SLAM [[pdf](https://arxiv.org/pdf/2105.11344.pdf)] [[code](https://github.com/PRBonn/OverlapNet)] 🔥

  - [Learning] [TITS] 3D LiDAR-Based Global Localization Using Siamese Neural Network [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8734150)] [[code](https://github.com/HuanYin94/LocNet_caffe)] 🔥

  - [Learning] [IROS] Semantic Graph Based Place Recognition for 3D Point Clouds [[pdf](https://arxiv.org/pdf/2008.11459.pdf)] [[code](https://github.com/kxhit/SG_PR)] 🔥


- 2019

  - [Learning] [CVPR] PCAN: 3D Attention Map Learning Using Contextual Information for Point Cloud Based Retrieval [[pdf](https://arxiv.org/pdf/1904.09793.pdf)] [[code](https://github.com/XLechter/PCAN)] 🔥


- 2018

  - [Handcraft] [IROS] Scan Context: Egocentric Spatial Descriptor for Place Recognition Within 3D Point Cloud Map [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593953)] [[code](https://github.com/gisbi-kim/scancontext)] 🔥

  - [Learning] [CVPR] PointNetVLAD: Deep Point Cloud Based Retrieval for Large-Scale Place Recognition [[pdf](https://arxiv.org/pdf/1804.03492.pdf)] [[code](https://github.com/mikacuy/pointnetvlad)] 🔥


- 2017

  - [Learning] [ICRA] SegMatch: Segment based place recognition in 3D point clouds [[pdf](https://arxiv.org/pdf/1609.07720/1000.pdf)] [[code](https://github.com/ZengYeGe/segmatch)] 🔥


- 2016

  - [Handcraft] [IROS] M2DP: A novel 3D point cloud descriptor and its application in loop closure detection [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7759060)] [[code](https://github.com/LiHeUA/M2DP)] 🔥


- 2015

  - [Handcraft] [IROS] A Fast Histogram-Based Similarity Measure for Detecting Loop Closures in 3-D LIDAR Data [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7353454)] [[code](https://github.com/wangliuliu/histogram)] 🔥



## LiDAR Place Recognition Datasets

- 2024
  - [Single/Multi] [IJRR] [OS2-128] [VLP-16] [Avia] [Aeva] Heterogeneous LiDAR Dataset for inter-LiDAR Place Recognition [[pdf](https://arxiv.org/pdf/2309.14590.pdf)] [[download](https://sites.google.com/view/heliprdataset)] 🚙
  
  - [Single/Multi] [IEEE Sensors Letter] [OS1-64] [OS1-32] DiTer: Diverse Terrain and Multi-Modal Dataset for Field Robot Navigation in Outdoor Environments [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10416213)] [[download](https://sites.google.com/view/diter-dataset/)] 🚙
  
  - [Multi] [RAL] [VLP-16] [Avia] BotanicGarden: A High-Quality Dataset for Robot Navigation in Unstructured Natural Environments [[pdf](https://arxiv.org/pdf/2306.14137.pdf)] [[download](https://github.com/robot-pesg/BotanicGarden)] 🤖


- 2023

  - [Single/Multi] [ICRA] [VLP-16] Wild-Places: A Large-Scale Dataset for Lidar Place Recognition in Unstructured Natural Environments [[pdf](https://arxiv.org/pdf/2211.12732.pdf)] [[download](https://csiro-robotics.github.io/Wild-Places/)] 🧔

  - [Multi] [IROS-workshop] [Mid-70] ConPR: Ongoing Construction Site Dataset for Place Recognition [[pdf](https://oravus.github.io/vpr-workshop/assets/accepted_papers/1_conpr_ongoing_construction_sit.pdf)] [[download](https://github.com/dongjae0107/ConPR)] 🧔

  - [Multi] [IJRR] [VLP-128] Boreas: A Multi-Season Autonomous Driving Dataset [[pdf](https://arxiv.org/pdf/2203.10168.pdf)] [[download](https://www.boreas.utias.utoronto.ca/#/)] 🚙

  - [Multi] [ISVC] [VLP-16] Multimodal Dataset for Localization, Mapping and Crop Monitoring in Citrus Tree Farms [[pdf](https://arxiv.org/pdf/2309.15332.pdf)] [[download](https://ucr-robotics.github.io/Citrus-Farm-Dataset/)] 🤖

  - [Multi] [RAL] [VLP-16] GRACO: A Multimodal Dataset for Ground and Aerial Cooperative Localization and Mapping [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10008011)] [[download](https://sites.google.com/view/graco-dataset)] 🛩️ 🤖

  - [Multi] [IJRR] [OS1-64] [OS1-32] Pohang Canal Dataset: A Multimodal Maritime Dataset for Autonomous Navigation in Restricted Waters [[pdf](https://arxiv.org/abs/2303.05555)] [[download](https://sites.google.com/view/pohang-canal-dataset)] 🚢

  - [Multi-Robot] [Arxiv] [VLP-16] S3E: A Large-scale Multimodal Dataset for Collaborative SLAM [[pdf](https://arxiv.org/pdf/2210.13723.pdf)] [[download](https://github.com/PengYu-Team/S3E)] 🤖

  - [Multi-Robot] [Arxiv] [VLP-16] Resilient and Distributed Multi-Robot Visual SLAM: Datasets, Experiments, and Lessons Learned [[pdf](https://arxiv.org/pdf/2304.04362.pdf)] [[download](https://github.com/MIT-SPARK/Kimera-Multi-Data)] 🤖


- 2022

  - [Multi-Robot] [RAL] [VLP-16] DiSCo-SLAM: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9662965)] [[code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)] 🤖


- 2021

    - [Single] [ICRA] [OS1-128] Robust Place Recognition using an Imaging Lidar [[pdf](https://arxiv.org/pdf/2103.02111.pdf)] [[code](https://github.com/TixiaoShan/imaging_lidar_place_recognition)] 🧔


- 2020

  - [Single/Multi] [ICRA] [OS1-64] Multimodal Range Dataset for Urban Place Recognition [[pdf](https://rpm.snu.ac.kr/publications/gskim-2020-icra.pdf)] [[download](https://sites.google.com/view/mulran-pr)] 🚙

  - [Single/Multi] [ICRA] [HDL-32] The Oxford Radar RobotCar Dataset: A Radar Extension to the Oxford RobotCar Dataset [[pdf](https://arxiv.org/pdf/1909.01300.pdf)] [[download](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/)] 🚙

  - [Single/Multi] [IROS] [HDL-32] EU Long-term Dataset with Multiple Sensors for Autonomous Driving [[pdf](https://arxiv.org/pdf/1909.03330.pdf)] [[download](https://epan-utbm.github.io/utbm_robocar_dataset/)] 🚙


- 2019

  - [Single] [IJRR] [VLP-16] Complex urban dataset with multi-level sensors from highly diverse urban environments [[pdf](https://journals.sagepub.com/doi/pdf/10.1177/0278364919843996)] [[download](https://sites.google.com/view/complex-urban-dataset/system?authuser=0)] 🚙


- 2016

  - [Multi] [IJRR] [HDL-32] North Campus Long-Term Vision and Lidar Dataset [[pdf](http://robots.engin.umich.edu/nclt/nclt.pdf)] [[download](http://robots.engin.umich.edu/nclt/)] 🤖


- 2013

  - [Single] [IJRR] [HDL-64] Vision meets Robotics: The KITTI Dataset [[pdf](https://journals.sagepub.com/doi/epub/10.1177/0278364913491297)] [[download](https://www.cvlibs.net/datasets/kitti/raw_data.php)] 🚙



## LiDAR Place Recognition with various algorithms

- 2023

  - [Multi-Robot SLAM] [IEEE Sensors Journal] DCL-SLAM: A Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10375928)] [[code](https://github.com/PengYu-Team/DCL-SLAM)] 🔥


- 2022

  - [Multi-Robot SLAM] [RAL] DiSCo-SLAM: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9662965)] [[code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)] 🔥

  - [Mapping Framework] [ICRA] LT-mapper: A Modular Framework for LiDAR-based Lifelong Mapping [[pdf](https://arxiv.org/pdf/2107.07712.pdf)] [[code](https://github.com/gisbi-kim/lt-mapper)] 🔥

  - [SLAM Framework] [ICEIC] SC-LiDAR-SLAM: A Front-end Agnostic Versatile LiDAR SLAM System [[pdf](https://arxiv.org/pdf/2201.06423.pdf)] [[SC-A-LOAM](https://github.com/gisbi-kim/SC-A-LOAM)] [[SC-LeGO-LOAM](https://github.com/gisbi-kim/SC-LeGO-LOAM)] [[SC-LIO-SAM](https://github.com/gisbi-kim/SC-LIO-SAM)] [[FAST-LIO-SLAM](https://github.com/gisbi-kim/FAST_LIO_SLAM)] 🔥



## Contact

- Hogyun Kim (hg.kim@inha.edu)
