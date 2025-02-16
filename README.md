# Image Captioning using ML

## Overview

This repository contains the implementation of an Image Caption Generator, leveraging a combination of Convolutional Neural Networks (CNNs) for image feature extraction and Long Short-Term Memory (LSTM) networks for generating descriptive captions.

![image](https://github.com/Shree1291/ImageCaptionCraft/assets/97882995/e88a841d-e5bd-4a65-baaf-039733aa5083)

## Caption Examples

### Actual Caption

- **Caption 1:**
  - _startseq baby girl in an orange dress gets wet as she stands next to water sprinkler endseq_
- **Caption 2:**
  - _startseq blonde toddler wearing an orange dress is wet and standing beside sprinkler in yard endseq_
- **Caption 3:**
  - _startseq child in dress is looking at sprinkler endseq_
- **Caption 4:**
  - _startseq little girl in an orange dress is running through the sprinkler in the yard endseq_
- **Caption 5:**
  - _startseq "on wet grass little blond girl in orange dress plays in sprinkler." endseq_

### Predicted Caption

- **Generated Caption:**
  - _startseq two girls in orange clothes are playing with sprinkler endseq_

## Features

- **Data Loading and Preprocessing:** Utilizes the Flickr8k dataset, encompassing image data and corresponding captions.
- **Feature Extraction:** Employs a pre-trained VGG16 model to extract features from images.
- **Caption Preprocessing:** Cleans and preprocesses captions for effective training.
- **Tokenization:** Implements a tokenizer to handle text data and create a vocabulary.
- **Model Architecture:** Structured combination of image and textual features for caption generation.
- **Training:** Model training through a data generator for efficient processing of large datasets.
- **Evaluation:** Utilizes BLEU scores for evaluating the quality of generated captions.
- **Caption Generation:** Functionality to generate captions for new images using the trained model.

## Usage

1. **Data Setup:** Ensure the Flickr8k dataset is available and properly formatted.
2. **Model Training:** Execute the provided Jupyter notebook to train the image caption generator model.
3. **Evaluation:** Evaluate the model's performance using BLEU scores on a test set.
4. **Caption Generation:** Use the trained model to generate captions for new images.

## Dependencies

- Python 3.x
- Pytorch
- Keras
- NumPy
- NLTK

## References

[1] Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan. "Show and Tell: A Neural Image Caption Generator." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2015. [Link to Paper](https://arxiv.org/abs/1411.4555)

- VGG16: [Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." arXiv preprint arXiv:1409.1556 (2014).](https://arxiv.org/abs/1409.1556)

## Acknowledgments

This project is part of a design project of Vth Semester for IIIT Vadodara - International Campus Diu. Feel free to explore, contribute, and adapt the code for your own image captioning projects!
