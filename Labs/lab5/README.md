# Lab5: Visual Image Captioning

![Visual Image Captioning](Image_Captioning.png)

## 1 - Objectives

* Building an Encoder-Decoder model for image captioning based on CNN and RNN.
* Implementing the attention mechanism and integrating it with the model.
* Learning how to deal with datasets that do not fit into RAM.
* Working with few tensorflow parts instead of tf.Keras.

## 2 - Flickr 8k Dataset
The Flickr dataset is used for image captioning. The dataset consists of images along with 5 captions for each image provided by human annotators.

![Flickr](Flickr.png)

We will be using Flickr 8k version which consists of 8000 images and their captions.

The training set has 6000 examples.

The testing set has 1000 examples.

You can find [the dataset on Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k), also you can fine many [code notebooks](https://www.kaggle.com/datasets/adityajn105/flickr8k/code) for the dataset on Kaggle. 

To easily use the dataset on Google Colab, we will obtain it in the notebook from this [github repo](https://github.com/jbrownlee/Datasets/releases/), since the official website took it down. 

## 3 - Requirements

* Solve [this notebook](lab5.ipynb) of the assignment and deliver a filled ipython notebook that shows the best output found in your experiments. **Check the hints in the notebook to help guide you while filling in the code**.
* Download the notebook and upload it for submission. **Make sure you include the output of the cells, especially the predicted caption on a test image in the evaluation section at the end** 
* No report is required.