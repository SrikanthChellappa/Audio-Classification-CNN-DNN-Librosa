# Audio-Classification-CNN-DNN-Librosa

We are using a subset of the data from ESC-50 dataset from https://dagshub.com/kinkusuma/esc50-dataset. The ESC-50 dataset is a labeled collection of 2000 environmental audio recordings suitable for benchmarking methods of environmental sound classification.
We will develop and train a model to classify 8 different environment sounds from the above dataset that has 50+ environment sound audio files for classification.

We will be using Librosa package to read each of the .wav files and convert them to melspectorgram which will then be further analysed through a neural netowrk architected with a set of CNN-DNN layers. Pls visit the original dataset link to download all wav 
files for 50 classfications to extend this model further. Also, Pls revisit the model architecture and fine-tune the parameters to improve the prediction accuracy
