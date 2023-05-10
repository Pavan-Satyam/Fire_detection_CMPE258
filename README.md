# Fire_detection_CMPE258

The project aims to detect the presence of fire in a given image using neural networks, with the motivation being to minimize property damage and save human lives by enabling early fire detection. The project will experiment with various neural network architectures to identify a model that can predict with high accuracy and in the least amount of time. The application of this project is in fire detection systems, which can be used by authorities to identify the location of the fire and extinguish it.

## DataSet

We used a dataset of images containing Fire and Non Fire images. URL:

## Methods

- InceptionNet_v3
- EfficientNet_B0
- EfficientNet_B7
- MobileNet_v2
- ResNet
- Custom Deep CNN

## Technical Requirements:

We used Google Colab Pro for executing the model.

## Execution 

These are the links to Colab notebooks:

*You need to mount the drive for the dataset. Make sure the paths are correct.*

Just run the Colab notebooks. If you encounter any difficulties, please email us at pavan.satyam@sjsu.edu, piyush.gade@sjsu.edu.

## Results

| Parameter | MobileNetV2 | RestNet |
| --- | --- | --- |
| Input shape | (224,224,3) | (224,224,3) |
| Weight | Initialized to ImageNet | Initialized to ImageNet |
| Loss function | Binary Cross Entropy Loss | Categorical Cross Entropy |
| Running time (epochs - 80) | 4 hours | 3 hours 28 minutes |
| Regularization | L2 Regularization | L2 Regularization |
| Dropout | 0.2 | 0.3 |
| Accuracy | 78% | 78% |

### Team:

- Pavan Satyam - pavan.satyam@sjsu.edu
- Piyush Gade - piyush.gade@sjsu.edu
- Alekhya Savihtri Pasupuleti - alekhyasavithri.pasupuleti@sjsu.edu
- Shravani Naikoti - shravani.naikoti@sjsu.edu
