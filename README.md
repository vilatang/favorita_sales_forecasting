# Favorita Sales Forecasting

## Introduction

Corporación Favorita has challenged the Kaggle community to build a model that more accurately forecasts product sales. [Link](https://www.kaggle.com/c/favorita-grocery-sales-forecasting)

We developed the pilot solution to demonstrate each key component of a Data Science project.

![alt text](https://www.elcomercio.com/files/article_main/uploads/2015/09/17/55fb1aa2ccd34.jpeg "Logo Title Text 1")


## Prerequisite
* [Anaconda 3](https://www.continuum.io/)
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [LGBM](https://github.com/Microsoft/LightGBM/)


## Instruction

##### Environment Setup

    conda create -n favorita python=3.6
    activate favorita
    conda install pandas matplotlib jupyter notebook scipy scikit-learn
    pip install tensorflow keras lightgbm

##### Run
Please note the source data files `train.csv`, `test.csv` and `items.csv` are not included in the repo. To run the code, first you need to download and copy them to the same path as the model code.

Lunch the Jupyter Notebook

    jupyter notebook
