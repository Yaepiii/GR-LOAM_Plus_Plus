# 面向地面机器人的通用鲁棒激光SLAM技术

这是我们之前工作[GR-LOAM](https://www.sciencedirect.com/science/article/pii/S0921889021000440)和[RGC-SLAM](https://ieeexplore.ieee.org/abstract/document/10654559)的进一步拓展，改进了之前的地面提取方案和特征提取方案，使得算法适用于各种型号的雷达。

另外，通过引入强度特征，以及几何相似性和强度相似性约束，使得算法取得更鲁棒的效果。

本文工作不开源，开源版本可见[RGC-SLAM](https://github.com/ROBOT-WSC/RGC-SLAM)，如果您对我们的工作感兴趣或我们的代码对您有用，请引用我们的工作：
```
@article{SU2021103759,
title = {GR-LOAM: LiDAR-based sensor fusion SLAM for ground robots on complex terrain},
journal = {Robotics and Autonomous Systems},
volume = {140},
pages = {103759},
year = {2021},
issn = {0921-8890},
doi = {https://doi.org/10.1016/j.robot.2021.103759},
url = {https://www.sciencedirect.com/science/article/pii/S0921889021000440},
author = {Yun Su and Ting Wang and Shiliang Shao and Chen Yao and Zhidong Wang}}

@ARTICLE{10654559,
  author={Wang, Shaocong and Cao, Fengkui and Wang, Ting and Shao, Shiliang and Liu, Lianqing},
  journal={IEEE Transactions on Intelligent Vehicles}, 
  title={Robust Ground Constrained SLAM for Mobile Robot With Sparse-Channel LiDAR}, 
  year={2024},
  volume={},
  number={},
  pages={1-12},
  keywords={Laser radar;Simultaneous localization and mapping;Feature extraction;Robots;Degradation;Point cloud compression;Odometry;SLAM;Mobile robot;Ground constraint;Degraded environment;Sparse-channel LiDAR},
  doi={10.1109/TIV.2024.3451137}}
```

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
