# PRODIGY_ML_03
Implement a support vector machine (SVM) to classify images of cats and dogs from the Kaggle dataset.

# Description
This project aims to develop a Support Vector Machine (SVM), that can classify Cats from Dogs. For this purpose, **SGDClassifier** model is used for SVM, and the model is trained on 20,000 images of Cats and Dogs. The model produces an average outcome of 0.51 accuracy per 50 images. With a large dataset, the model is trained in batches of 20 images.

# Dataset
The dataset used in this project is **Dogs-vs-Cats** Dataset, available in Kaggle. The dataset contains over 25,000 annotated images of Dogs and Cats, and, 10,000 unannotated images for testing. The images are converted to 'Grayscale', then, to numpy 1-D arrays for better processing.

[Dataset Link](https://www.kaggle.com/c/dogs-vs-cats/data)

# Inference
![SVM Model Inference](https://github.com/LogeswaranSR/PRODIGY_ML_03/assets/131794661/964a2799-99fa-4e40-8880-cb13c05b18f0)
