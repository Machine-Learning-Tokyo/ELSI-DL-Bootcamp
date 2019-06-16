# ELSI-DL-Bootcamp
Intro to Machine Learning and Deep Learning for Earth-Life Sciences

## Slides

### [ML Research Project Management](https://docs.google.com/presentation/d/1y4v1WdDILWbbqPQzEO8W4v33dVoCFl5I_04dTFyJZoE/edit?usp=sharing)

### Intro to Deep Learning

## Notebooks

### Exploratory Data Analysis

### Train a Convolutional Neural Network

**Data**: Kaggle - [DeepSat (SAT-6) Airborne Dataset](https://www.kaggle.com/crawford/deepsat-sat6)

405,000 image patches each of size 28x28 and covering 6 landcover classes

**Content**
- Each sample image is 28x28 pixels and consists of 4 bands - red, green, blue and near infrared.
- The training and test labels are one-hot encoded 1x6 vectors
- The six classes represent the six broad land covers which include barren land, trees, grassland, roads, buildings and water bodies.
- Training and test datasets belong to disjoint set of image tiles.
- Each image patch is size normalized to 28x28 pixels.
- Once generated, both the training and testing datasets were randomized using a pseudo-random number generator.

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/ELSI-DL-Bootcamp/blob/master/deepsat.png" width="600"></p>](https://www.kaggle.com/crawford/deepsat-sat6)
