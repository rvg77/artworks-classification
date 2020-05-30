# Artworks classification

In this work I will try to solve artist classification problem based on [**"Best Artworks Of All Time"**](https://www.kaggle.com/ikarus777/best-artworks-of-all-time) dataset using `TensorFlow 2.0`. 

## Content

* [`artworks.ipynb`](https://github.com/rvg77/artworks-classification/blob/master/artworks.ipynb): jupyter notebook containing all work
* [`artworks.pdf`](https://github.com/rvg77/artworks-classification/blob/master/artworks.pdf): copy in pdf format for instant view

## Dataset description

After being challenged many times by my girlfriend about who is the best to guess the painter, I decided to use the power of machine learning to defeat her.
I gathered a collection of artworks of the 50 most influential artists of all time. I added a dataset with basic information retrieved from wikipedia. I planned to create a convolutional neural network to recognise the artists looking the colors used and the geometric patterns inside the pictures.

### Dataset content

This dataset contains three files:

* `artists.csv`: dataset of information for each artist
* `images.zip`: collection of images (full size), divided in folders and sequentially numbered
* `resized.zip`: same collection but images have been resized and extracted from folder structure

Use resized.zip allows you to download less data and process faster your model.

## Inspiration

My goal is to create a model that learn to identify the artist analysing new pictures. I hope to learn new techniques or see some interesting usage of this data.

![](https://sun9-51.userapi.com/c858136/v858136162/1c0b61/GwA18z9fPIg.jpg)
