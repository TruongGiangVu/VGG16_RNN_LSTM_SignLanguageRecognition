# Sign Language Recognition

## Sections
- [Description](#description)
- [Dataset](#dataset)
- [Methods](#methods)
- [Getting Started](#getting-started)
## Description
<p>The project of graduation essay.</p>
<p>In this work, we have applied Deep Learning for sign language recognition. VGG16, RNN and LSTM were used.</p>

***Menber***
* Vu Truong Giang
* Tat Tran Phong

## Dataset
We use LSA64: A Dataset for Argentinian Sign Language <br />
It is available on [Link](http://facundoq.github.io/datasets/lsa64/).

## Methods
**VGG16 + LSTM method:**
> VGG16_LSTM_Train : file for training by LSTM model
> 
> CM_VGG16_LSTM_Test : file for testing LSTM model on test set

**VGG16 + RNN method:**
> VGG16_RNN_Train : file for training by RNN model
> 
> CM_VGG16_RNN_Test : file for testing RNN model on test set

## Getting Started
<p>Library: NumPy, os, Matplotlib, Tensorflow, Keras, Sklearn, opencv, Pandas, Seaborn</p>

***LSTM model***
- Run file *VGG16_LSTM_Train.ipynb* to train data and create weights.
- Run file *CM_VGG16_LSTM_Test.ipynb* for testing model and showing result.

***RNN model***
- Run file *VGG16_RNN_Train.ipynb* to train data and create weights.
- Run file *CM_VGG16_RNN_Test.ipynb* for testing model and showing result.
