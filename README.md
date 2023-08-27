# Deep learning course - project I

This repository contains code needed to reproduce the results for project I of the Deep Learning course.

---
## Description
Project I of the Deep Learning course is concerned with the application of convolutional neural networks (CNNs) to the image classification task on the CIFAR-10 dataset. In recent years, this type of neural networks has achieved state-of-the-art results in many complex tasks ranging from general computer vision problems (beginning with the famous AlexNet) through achieving super-human performance in chess and its variants, proving to this day it’s
general applicability and high performance in comparison to e.g. classical dense neural networks. Recently, a shift in the domain of computer vision based on deep neural networks has been observed due to the introduction of a Transformer-based architecture (initially  ntroduced in the context of natural language processing) called Vision Transformer (ViT). This family of neural networks outperforms convolutional neural networks under conditions of very large number of parameters and data. This transition, from dense neural networks to CNNs to visual transformers, is the motivation behind the experiments that we’ve conducted.


---
## Results
We presented obtained results in short [report](https://github.com/Wladeko/deep-learning-cnn/blob/main/report.pdf).

---
## Results replication
### Getting the dataset

To be able to run the experiments:

- download the CIFAR-10 dataset from [Kaggle](https://www.kaggle.com/competitions/cifar-10/overview)
- place the downloaded directory in the root directory of this repository
- unpack `train.7z` and `test.7z` inside it

### Creating a conda environment

To create proper conda environment, use

`conda create --name myenv --file conda_requirements.yml`

or

`conda create --name myenv --file conda_requirements.txt`

in root directory of this repository.

### Running experiments

To run an experiment, use

`python -m experiments/_X/exp.py`

where X - number of the experiment.

---
## Co-author
Be sure to check co-author of this project, [Bartek](https://github.com/sobieskibj).