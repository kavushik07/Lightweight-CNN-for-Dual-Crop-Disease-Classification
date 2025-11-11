# 🌿 Tomato & Cotton Leaf Disease Classification using 2D CNN

This project focuses on developing a **lightweight 2D Convolutional Neural Network (CNN)** model in **Python** to classify diseases in **tomato** and **cotton** leaves.  
The model achieves **high accuracy and efficiency** through optimized preprocessing, architecture tuning, and interpretability techniques.

---

## 🚀 Project Overview
- Built a **3-layer CNN** model with **Batch Normalization** and **Dropout** to prevent overfitting.  
- Applied **image preprocessing** and **data augmentation** to enhance model generalization.  
- Evaluated using **Accuracy**, **Confusion Matrix**, and **ROC Curves**.  
- Used **Grad-CAM visualizations** for model interpretability.  
- Datasets sourced from:
  - [Plant Village](https://www.kaggle.com/datasets/emmarex/plantdisease)
  - [Cotton Leaf Infection Dataset]
- Implemented and trained using the **Adam optimizer** for optimal convergence.

---

## 📁 Dataset Information
The dataset will be **mounted from Google Drive** during runtime to avoid large file uploads in the repository.  
You can modify the code to mount your Drive as shown below:

```python
from google.colab import drive
drive.mount('/content/drive')

# Example dataset path
dataset_path = '/content/drive/MyDrive/Datasets/LeafDiseaseDataset/'
