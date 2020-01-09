# CFENet_Cascaded-Feature-Enhancement-Network

Code for our article (High-Low Level Features Enhancement with Improved Attention Method for Medical Image Segmentation).
This paper proposes a Low-level Feature Enhancement Module (LFH), a High-level Feature Enhancement Module (HFE) and a Cascaded
Feature Enhancement Network. We evaluated our CFENet and proposed modules on three challenging datasets of skin lesion segmentation in
dermoscopic images, segmentation of brain tumors in magnetic resonance (MR) images and 3D VBs segmentation.
![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/Network.png)

# Skin lesion segmentation
The skin lesion dataset can be downloaded from ISIC 2017: https://challenge.kitware.com/#challenge/583f126bcad3a51cc66c8d9a.
The ISIC 2017 challenge dataset contains a total of 2,750 dermoscopy images, of which 2,000 were used for training, 150 were used for validation and the last 600 were used for testing.
Our experimental results are shown in the table below.

![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/skin_result-1.png)
![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/skin_result-2.png)


# Brain tumors segmentation
The Brain tumors dataset can be downloaded from BraTS 2018: https://www.med.upenn.edu/sbia/brats2018.html.
we used 155 volumes with 12400 slices for training, 50 volumes with 4000 slices for validation and 80 volumes with 6400 slices for testing.
Our experimental results are shown in the table below.

![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/BraTs_result-1.png)
![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/BraTs_result-2.png)


# 3D Vertebral Bodies Segmentation
The VBs segmentation dataset can be downloaded from:https://zenodo.org/record/22304#.XhambegzZPY.
This dataset contains a total of 23 MR images. So, we use 4-fold cross validation to evaluate the performance of the networks.
Our experimental results are shown in the table below.

![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/VBs-result-1.png)
![image text](https://github.com/WH-HuanWang/CFENet/blob/master/img-storage/Vbs-result-2.png)


# Requirements
Pytorch 1.0, and Jupyter Notebook
