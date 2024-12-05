# Trash-classification-5550

### Introduction

The rapid growth of urbanization and industrial production has significantly impacted the environment, leading to an alarming increase in waste generation. Managing this waste effectively has become a global priority. **Recycling**, a key solution to this challenge, transforms waste into valuable resources through proper sorting and processing. This project focuses on enabling automated systems, such as smart waste-sorting robots and intelligent waste bins, to classify waste accurately by analyzing trash images.

This tutorial outlines the step-by-step process of training the lightweight Convolutional Neural Network (CNN) **EfficientNet-B0** on a custom dataset of 2,527 images representing different types of trash. The resulting model serves as a foundation for lightweight waste management image classification systems, designed for real-world applications such as live deployment in smart bins.

---

#### About EfficientNet

**EfficientNet** is a family of models (B0–B7) that balance computational efficiency and accuracy. Higher-numbered models require more computational resources and larger datasets, while lower-numbered models are lightweight and suitable for resource-constrained environments. 

For this project, we selected the **EfficientNet-B0** CNN model due to its efficiency, ease of training, and minimal computational demands. This lightweight model is ideal for deployment in distributed systems, such as smart bins, where compactness and low-power requirements are critical.

---

#### About Our Data
The dataset used for this project is the [TrashNet Dataset](https://www.kaggle.com/datasets/feyzazkefe/trashnet), 
Our dataset is imported from the Kaggle directory of **Gary Huang and Mindy Yang's** TrashNet repository (FeyZazkefe on Kaggle). It contains 2,527 images of trash, distributed across six categories:

1. **Cardboard**: 403 images
2. **Glass**: 501 images
3. **Metal**: 410 images
4. **Paper**: 594 images
5. **Plastic**: 482 images
6. **Trash**: 137 images
