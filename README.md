# Image-Captioning
Aim is to generate caption for given image
Concept used
- Data preprocessing (include images as well as caption)
- Used word embedding
- Used CNN for working on images
- Used RNN for working on text
- Transfer learning (feature extraction)
- Use MLP which take input of image feature and text feature and output next text

## Example
![alt Bike](https://github.com/adityamudgil2505/Image-Captioning/blob/main/assets/Bike.png)
![alt Football](https://github.com/adityamudgil2505/Image-Captioning/blob/main/assets/Football.png)

## Steps
- Data collection
- Understanding the data
- Data Cleaning
- Loading the training set
- Data Preprocessing — Images
- Data Preprocessing — Captions
- Data Preparation using Generator Function
- Word Embeddings
- Model Architecture
- Inference

## Dataset
Flickr8k from https://github.com/text-machine-lab/MUTT/raw/master/data/flickr/Flickr8k.token.txt
Use 6K for training, 1K for Validation and 1K for testing

## Model architecture
![alt Model](https://github.com/adityamudgil2505/Image-Captioning/blob/main/assets/model.jpeg)

## Reference
https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8
