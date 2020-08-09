# Bamboo Forest Detection

# Introduction
We will detect `bamboo forest` without using specialized  networks like U-net, but with a general CNN for classification, we still can perform a segmentation. The concept originates from the "Patch-based Classification", proposed in the following paper. We will combine a sliding window patches with repetitive CNN classification which allows detection of tumor region(s).

Watanabe et al., performed a similar approach to segment bamboo forests from satelite images retreived from google earth. They express their method as "chopped images", however paying respect to the previous research, I describe this method as "Patch-based Classification". 


**Deep Learning for Identifying Metastatic Breast Cancer**

https://arxiv.org/abs/1606.05718
![image](https://raw.githubusercontent.com/totti0223/deep_learning_for_biologists_with_keras/master/assets/cancer.png)



