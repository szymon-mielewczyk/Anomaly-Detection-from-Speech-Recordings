# Anomaly Detection from Speech Recordings

### Project for detecting anomalies from speech recordings using an ML model with unsupervised learning. Anomalies were recorded and added to the speech from datasets. 

### Model was trained in 2 phases

### Phase 1: Unsupervised Learning | Self-Supervised Learning

#### Input: CQT image of shape (,1,84,44)

#### Output: Vector of shape (,32) 

#### Loss function: Triple loss

### Phase 2: Self-Supervised Learning | Training the last additional layer with the rest of the model being frozen

#### Input: Vector of shape (,32) 

#### Output: Vector of shape (,2) 

#### Loss function: MSE Loss

## Datasets

### The LJ Speech Dataset

https://www.kaggle.com/datasets/mathurinache/the-lj-speech-dataset

### RAVDESS Emotional speech audio

https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio