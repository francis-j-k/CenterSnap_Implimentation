# Multi-Object 3D Shape Reconstruction and 6D Pose and Size Estimation


This repository is the implementation of CenterSnap paper:
**CenterSnap: Single-Shot Multi-Object 3D Shape Reconstruction and Categorical 6D Pose and Size Estimation**<br>

This paper explores the complex problem of simultaneous multi-object 3D shape reconstruction and 6D pose and size estimation in environments with object occlusions, using a single-view RGB-D observation.
Our initial investigations were inspired by works such as BundleTrack [1] and BundleSDF [2], which address 6D pose estimation and reconstruction. However, due to computational constraints and the need for version adaptability, our focus shifted towards working with an alternative approach within this domain. In this work, we present ObjectVue, an implementation from scratch of CenterSnap [3] a pioneering and computationally efficient, single-shot approach that radically diverges from traditional multi-stage pipelines which rely on predefined CAD models for multi-object pose estimation, size estimation and object reconstruction. ObjectVue builds on this foundation, aiming to enhance and streamline the process of simultaneous multi-object 3D shape reconstruction and 6D pose and size estimation, particularly in challenging scenarios involving object occlusions. Our method, trained and evaluated on the NOCS REAL 275 dataset, has been compared to the performance metrics of CenterSnap [3]. Our implementation, however, shows an 8.3% deterioration in mean Average Precision (mAP) for 6D pose estimation of novel real-world objects, indicating less accuracy. Despite this, ObjectVue demonstrates commendable results when compared to other methodologies and stands out as a strong candidate for advanced applications in robotics and computer vision

By: Francis Jacob Kalliath, Thejaswini Goriparthi

Create a python 3.8 virtual environment and install requirements:

```bash
cd git clone git@github.com:francis-j-k/CenterSnap_Implimentation.git
```

Or else

Run the jupyter Notebook on a google colab with a T4 GPU 
