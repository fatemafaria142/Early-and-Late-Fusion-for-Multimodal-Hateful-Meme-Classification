# Integrating-Early-and-Late-Fusion-for-Multimodal-Hateful-Meme-Classification

This repository contains code for Multimodal Hateful Meme Classification using Early Fusion and Late Fusion techniques.

## Dataset
- **Dataset Name**: Facebook Hateful Meme Dataset
- **Dataset Link**: [Facebook Hateful Meme Dataset](https://www.kaggle.com/datasets/parthplc/facebook-hateful-meme-dataset/data)

## Overview
This project explores the application of Early Fusion and Late Fusion for Multimodal Hateful Meme Classification. It combines visual information from pretrained CNN models and textual information from pretrained BERT models to classify hateful memes.

### Early Fusion and Late Fusion in Multimodal Learning

#### Early Fusion:
Early Fusion, also known as feature-level fusion or data-level fusion, involves merging information from multiple modalities at an initial stage, creating a single unified representation that encompasses all modalities. In the context of multimodal hateful meme classification:

- **Explanation**: Early Fusion combines features extracted from different modalities (such as images and text) into a joint representation before passing it through the classification model.


#### Late Fusion:
Late Fusion, or decision-level fusion, involves integrating decisions or predictions made independently by models operating on distinct modalities at a later stage of the process.

- **Explanation**: Instead of combining features at the beginning, Late Fusion combines decisions or predictions made separately by models operating on each modality.



## Pretrained Models Used
### Pretrained CNN Models
- ResNet50
- ResNet152
- VGG19
- MobileNet V2
- MobileNet V3
- DenseNet121
- DenseNet201

### Pretrained BERT Model
- mBERT


