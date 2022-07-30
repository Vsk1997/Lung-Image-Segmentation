# Lung-Image-Segmentation
---

Lung segmentation is an important step in developing a Computer-aided Diagnosis (CAD) system for thediagnosis of lung illnesses in radiographs. In this project, a model based on Residual U-net (ResUnet) architecture is used to segment the lung from the CXR images. The area of interest must be first separated from the entire image. Through segmentation, it aims to divide the image in a series of region based on the characteristics of the image that are almost constant in each of the region. 

The aim of medical image segmentation is to extract quantitative information (eg, volumetric data, morphometric data, textural patterns–related information) with regard to an organ of interest or a lesion within the organ.

In general, a segmentation problem can be considered as consisting of two related tasks:
- Object recognition: Object recognition is the determination of the target object’s whereabouts on the image or its location
- Object delineation: Object delineation draws the object’s spatial extent and composition

---

Considering the very small number of images in training and to achieve good results, the project aims,
- to identify CXR images and its equivalent lung mask to be used in training the model.
- Develop a model based on Deep Residual U-Net Architecture to segment the lungs from CXR image for lung disease detection.

<p align="center">
  <img width="400" height="200" src="https://user-images.githubusercontent.com/37743343/181909259-538afd91-45ef-4a0e-ad41-0ff77d7d4b0e.png">
</p>

