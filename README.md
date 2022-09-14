# Image-Captioning-using-CNN-RNN-models

EYE FOR BLIND

A project for generating an audio description of images. This kind of model has potential applications for blind people so that they can understand any image with the help of speech descritions.

It is comprised of a deeplearning model based on encoder-decoder architecture with attention mechanism. This project is based on an extension of the paper, "Show, Attend and Tell: Neural Image Caption Generation with Visual Attention".

Given that we need to generte a text caption, this model involves both image understanding and NLP. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library.

The Flicr8K dataset is used for training this model. The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.
