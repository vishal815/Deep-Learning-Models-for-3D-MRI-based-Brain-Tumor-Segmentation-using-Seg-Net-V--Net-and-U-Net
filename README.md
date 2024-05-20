# Novel Architecture and Comparative Study for Deep Learning-Based Segmentation of 3D Brain MRI Images using SegNet, V-Net, and U-Net

<p align="center">
https://github.com/vishal815/Deep-Learning-Models-for-3D-MRI-based-Brain-Tumor-Segmentation-using-Seg-Net-V--Net-and-U-Net/assets/83393190/cc8f7b21-a600-44a9-b4c0-b5160b25dfa4
</p>

## Abstract
Brain tumor detection is an essential undertaking in the fields of neuroimaging and medical image analysis. It detects the abnormal growth of tissues within MRI scans. In the past, manual detection was performed, which was less effective and time-consuming. Then the transition shifted to 2D images, which enhanced the accuracy and efficiency of brain tumor detection compared to manual methods. The integration of artificial intelligence with brain tumor detection processes has completely transformed the field. Modern hardware, like GPUs and deep learning algorithms, particularly CNN, have enabled the use of large datasets for training, reducing processing time and improving scalability.

This research includes 3D brain MRI images of tumor segmentation using different CNN architectures: SegNet, V-Net, and U-Net. Implemented a novel architecture of UNet with the latest methodologies in which a symmetrical encoder-decoder design is formed with Leaky ReLU activation, dropout layers, and batch normalization layers for regularization and GELU activation to preserve spatial information. Medical Segmentation Decathlon datasets are used to train and test models in experimentation. The research evaluates these models based on complexity, training time, and segmentation accuracy. U-Net emerges as the top performer with a Dice Similarity Coefficient of 88.5%, surpassing V-Net (86.4%) and SegNet (84.8%).

<p align="center">
  <img src="https://github.com/vishal815/Deep-Learning-Models-for-3D-MRI-based-Brain-Tumor-Segmentation-using-Seg-Net-V--Net-and-U-Net/assets/83393190/0f7b395e-373b-42c9-8c69-1662dd0244b1" alt="Input and Output">
  <img src="https://github.com/vishal815/Deep-Learning-Models-for-3D-MRI-based-Brain-Tumor-Segmentation-using-Seg-Net-V--Net-and-U-Net/assets/83393190/d6693d84-cc29-4397-98d3-952ae3ae0748" alt="Dice Coefficient">
</p>

## Overview
Brain tumor detection is a critical task in the fields of neuroimaging and medical image analysis. Detecting abnormal tissue growth within MRI scans is essential for accurate diagnosis and treatment planning. In the past, manual detection methods were less effective and time-consuming. However, advancements in deep learning and artificial intelligence have transformed brain tumor detection.

This research project focuses on 3D brain MRI image segmentation using three popular CNN architectures: SegNet, V-Net, and U-Net. We also propose a novel architecture based on U-Net, incorporating Leaky ReLU activation, dropout layers, batch normalization, and GELU activation to preserve spatial information. The study evaluates these models based on complexity, training time, and segmentation accuracy.

<p align="center">
  <img src="https://github.com/vishal815/Deep-Learning-Models-for-3D-MRI-based-Brain-Tumor-Segmentation-using-Seg-Net-V--Net-and-U-Net/assets/83393190/032f08d4-c3be-408b-9b3a-36723e91b209" alt="U-Net Novel Architecture">
</p>

## Code and Dataset
- **Code Repository:** [GitHub - My Final Project](https://www.kaggle.com/code/vishallazrus/my-final-project)
- **Dataset:** [Medical Segmentation Decathlon](http://medicaldecathlon.com/)

## Motivation
A primary malignant brain tumor has a poor prognosis, significantly impacting patients’ quality of life. Early detection using advanced imaging modalities (such as MRI) is crucial for better patient outcomes.

## Literature Review
Integration of medical science and artificial intelligence is cutting-edge research. Researchers focus on accurate tumor classification and 2D/3D image segmentation. 3D MRI images provide precise results, but segmenting volumetric data remains challenging due to noise and computational requirements.

## Conclusion
Brain tumor segmentation using deep learning techniques enhances diagnosis, treatment planning, and patient monitoring. Our novel U-Net architecture shows promising results.

<p align="center">
  <img src="https://github.com/vishal815/Deep-Learning-Models-for-3D-MRI-based-Brain-Tumor-Segmentation-using-Seg-Net-V--Net-and-U-Net/assets/83393190/5b694226-283b-4473-b1f5-b70642966451" alt="Table of Models">
</p>
