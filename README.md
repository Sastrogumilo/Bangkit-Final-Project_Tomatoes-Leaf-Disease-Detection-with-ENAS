# Tomato Leaf Disease Detection using CNN-ENAS
Disclaimer: This project was created to fulfill Bangkit Academy Final Assessment. You can reproduce it by opening our Notebook file inside `Notebook` directory (`TomatoesV2.ipynb`) and run all the cells inside Google Colab. (Preferably using GPU Runtime)

Created by Nala Aldina, Candra Dewi, Muhammad Pandam, and Achmad Fauzan.

## Description
This project aims to develop a model to diagnose tomato leaf disease using [Efficient Neural Architecture Search](https://arxiv.org/abs/1802.03268) (ENAS) we were using micro search strategy to find the optimum blocks of architecture for Convolutional Neural Network (CNN).

Dataset: [Tomato leaf disease detection](https://www.kaggle.com/kaustubhb999/tomatoleaf)
In this dataset, there are 11,000 images for all classes that is listed down below:
1. Tomatomosaicvirus
2. Target spot
3. Bacterial spot
4. Tomato Yellow Leaf Curl Virus
5. Late blight
6. Leaf mold
7. Early blight
8. Spidermites Two-spotted Spidermite
9. Healthy
10. Septoria leaf spot

Dependencies:
- Tensorflow 2.2.0
- Matplotlib 3.2.1
- Numpy 1.18.4
- ImageCV 4.1.2
- Hyperactive (install using `pip install Hyperactive`)

## Result
The model is able to gain ~93% accuracy, higher than the baseline model which is only ~86%.

The APK file can downloaded [here](https://drive.google.com/file/d/1EFjDhopJe0cLTvWdr4Evl0AxnGne4M2W/view)

