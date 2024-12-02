# Synthetic_DFU
Synthetic Images with Dense Annotations and Ensemble Learning for DFU Segmentation

DFUC2022.
ICPR2024.
DOI：https://doi.org/10.1007/978-3-031-78398-2_23

1.使用FreestyleNet生成合成数据集
https://github.com/essunny310/FreestyleNet
![image](https://github.com/user-attachments/assets/e3bb14eb-7e4c-48e9-b901-9c86aef701ab)

2.误差像素过滤操作
FreeMask：https://github.com/LiheYoung/FreeMask
![image](https://github.com/user-attachments/assets/b179b1cd-efd8-46a8-805f-c2a24b36fe11)

3.重采样操作
可根据公式、方法实现

4.集成学习
参考tools文件夹内容。

本文训练各个模型的代码基于mmsegmentation（https://github.com/open-mmlab/mmsegmentation）实现。


我们的方法在DFUC2022实时排行榜中排名第二！
![image](https://github.com/user-attachments/assets/16746617-c4d7-4d50-b418-4086c3e93398)

