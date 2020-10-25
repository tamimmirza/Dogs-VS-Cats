# Cats VS dogs

Kaggle Classification Challenge on classifying dogs and cats using Transfer Learning.

This was originally a challenge in building a classifier aimed at the world's best Machine Learning and AI Practitioners but the technology has advanced so quickly, you'll see how you can do it in just a few minutes with some simple Convolutional Neural Network programming.

Also, you may notice some warnings about missing or corrupt EXIF data as the images are being loaded into the model for training. Don't worry about this -- it won't impact your model! :)

I like cats better than dogs so they come first :D

[Dogs VS Cats dataset from Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)

We will be using the following packages:
* **Pandas** - To format the data.
* **Scikit-learn** - To pre-process the data for training and validation.
* **TensorFlow 2** - To implement transfer learning and then train and evaluate the model.
* **Matplotlib** - To visualize the accuracy and loss during training and validation.

#### NOTE: This is not a submission for the Kaggle competition but a detailed analysis on how to classify this dataset

# Tools

## Software

| Packages  | Version  |
|---|---|
| Python  | 3.8  |
|  TensorFlow | 2.3  |
| NVIDIA CUDA Toolkit (If using GPU)  | 10.1  |
| NVIDIA cuDNN (if using GPU)  | 7.6  |

#### To install the necessary packages, activate your python environment and run this code (tensorflow comes bundled with CPU and GPU support):

```
pip install tensorflow scikit-learn matplotlib pandas 
```


## Hardware

| Hardware  | Memory  |
|---|---|
|  RAM | 16.0 GB  |
| NVIDIA GeForce GTX 1050 (Mobile)  | 4.0 GB  |
| Hard Drive  | 1.0 TB  |

# Results

#### InceptionV3 model was trained and evaluated on 20 epochs

| Metric  | Accuracy  |  Loss |
|---|---|---|
| Training  | 93.10%  | 0.2042 |
|  Validation |  96.70% | 0.1316  |