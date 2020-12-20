---
aliases: [arm]
title: 带触觉传感器的触摸机械臂开发与研究
summary: 
    <strong>同济大学实验室, 指导老师.[助理教授齐鹏](http://orcid.org/0000-0003-0514-9464)</strong><br>
    👌 设计了一种带有触觉传感器的新型机器手，以探索物体表面性质<br>
    👌 提出了一种基于触觉力的表面跟踪算法，可以跟踪具有不连续曲面的不规则物体的表面，并使用前馈神经网络对物体表面进行分类<br>
    👌 Designed a feed forward neural network to classify objects with different adjectives, i.e. soft-smooth soft-rough, hard-smooth, hard-rough<br>z
    📒 提交一篇论文到机器人顶会2021ICRA[C.2]<br> 
abstract: ""
date: "2020-11-07T16:56:12.584Z"
image:
  filename: featured.png
  focal_point: Smart
  preview_only: true
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://arm.rbind.io/
- icon: github
  icon_pack: fab
  name: materials
  url: https://github.com/rstudio-education/rmarkdown-extensions-conf19

categories:
- Robotics
tags:
- Tactile Interaction
- Robotics
- Neural Network

---

为了有效地与物理世界进行交互，智能机器人需要具备获取未知物体细节特征的能力。视觉设备通常用于检测对象的全局几何形状; 然而，使用这些设备无法识别表面性质等详细信息。本研究提出一种自适应触觉探测方法，利用智能指尖识别物体表面的物理性质。我们的表面跟随算法利用指尖与目标物体接触点处的法向力向量和切向力向量来预测目标物体的运动方向并实现表面探测。此外，引入修正指数K来调整不规则物体的滑动速度和表面跟随。仿真和室内实验都证明了该算法的鲁棒性和优越性。最后，我们提出并探索一种触觉预测神经网络，使我们的机器人能够通过物理交互获得准确的感觉。该模型的整体精度为90.2%。