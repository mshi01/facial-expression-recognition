# Facial Expression Recognition with Deep Learning

:seedling: This repo contains my contributions to our group project for Fall 2024 CS7643: Deep Learning in the OMSCS program. It includes:

- Building a training pipeline for the FER2013 dataset using PyTorch and evaluating the performance of several deep learning models.
- Implementing Grad-CAM to visualize key regions of images that contribute to emotion classification for the FER2013 and JAFFE datasets.

:seedling: Datasets: 
- [FER2013] (https://www.kaggle.com/datasets/deadskull7/fer2013)
- [JAFFE] (https://zenodo.org/records/3451524)

:seedling: Models:
- ImageNet pretrained ResNet18
- ResEmoteNet [Reference] (https://arxiv.org/abs/2409.10545)
- Deep-Emotion [Reference] (https://arxiv.org/abs/1902.01019)
- CustomCNN: A 9-layer CNN and a batch normalization layer added after each convolutional layer.
  
:seedling: Group Project Abstract: 
- Facial expressions are one of the most important parts of human communication. The ability to recognize facial expressions enables numerous applications in human-computer interaction and other areas. Diverse types of deep learning models have been utilized or specifically designed for Facial Expression Recognition (FER) tasks. Our study aims to better understand and compare different existing deep learning models used in FER. We seek to analyze the impact of various factors, including architectural differences, data augmentation, transfer learning, class balancing, and ensembling, on model performance. Additionally, we leveraged visualization techniques to identify facial regions that contribute to emotion recognition.
