# CategoriCrop

A from-scratch CNN to classify crop types from aerial photographs, 
built as part of Siraj Raval's Machine Learning Bootcamp, October 2019.

## Dataset

UAV aerial imagery from the Kaggle weed detection dataset — 15,336 
image segments across four classes: soil, soybean, grass, and broadleaf 
weeds. Segments were generated using the SLIC algorithm and manually 
annotated.

## Approach

Convolutional neural network built from scratch in Keras/TensorFlow. 
The notebook also explores a secondary direction — soil type 
classification across sandy, silt, clay, and loamy categories — 
before concluding that the available soil segments lacked the labels 
needed to pursue it within the available time.

## Status

Completed for bootcamp submission, October 2019. Not maintained.
