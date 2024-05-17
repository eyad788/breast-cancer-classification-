# MedicalCNN
Breast Cancer Classification using CNN with Transfer Learning Models : Breast cancer is the deadliest and most common cancer in the world. Early treatment of this cancer can help to nip it in the bud. In present medical setting, this cancer is identified by manual clinical procedures, which can lead to human errors and further delay the treatment procedure.
This project aims to perform abnormality classification by means of Convolutional Neural Networks. The datasets of interest are the CBIS DDSM and breakhis.
# About Datasets
DDSM is data base of 2,620 scanned film mammography studies which contains normal,benign,malignant cases with verified pathology information.
number of images used was 1000 image of total images, with a percentage of 50% benign and 50% malignant
data then was divided into a percentage of 60% train,20% test and 20% validation

breakhis dataset contains 2,480 benign and 5,429 malignant.an equal number of images is used 4,960 in total (2,480 benign and 2,480 malignant)

![image](https://github.com/eyad788/breast-cancer-classification-/assets/77728723/f7abe312-76eb-42f9-91fb-2fe975e03ab9)                      
![image](https://github.com/eyad788/breast-cancer-classification-/assets/77728723/968e6464-4482-4b40-aaae-5ded54073ea7)
# Experimantal Results
We pursued five different models to improve recall for both Datasets:
1. DenseNet201
2. VGG19
3. ResNet50
4. Incepton V3

Experimantal Results for DDSM dataset
![image](https://github.com/eyad788/breast-cancer-classification-/assets/77728723/664b844a-7aff-46fd-8979-bef47622dab3)
Experimantal Results for Breakhis dataset
![image](https://github.com/eyad788/breast-cancer-classification-/assets/77728723/2ddc902d-bed8-40af-a996-f1b33af84112)


The results show that Densenet201 model fits both datasets with 85% accuracy for mammogram and 92.3% accuracy for histopathology dataset.
# Tools

This project was developed using the following technologies:

- Python: scripting language
- Keras: open-source library for experimentation with deep neural networks
- Google Colab: free cloud-based Jupyter notebook environment by Google




