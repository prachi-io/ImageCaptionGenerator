# ImageCaptionGenerator
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

The goal of this project is to recognize the **context of an image** and annotating it with relevant captions using **deep learning, and computer vision.**
<br>
- It includes the labeling of an image with English keywords with the help of datasets provided during model training.


## How to run the code
[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg) [![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg) [![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)
- Make a **data** folder and download the following data set : 
<code><a href="https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip">Flicker8k_Dataset </a></code> &nbsp;
<code><a href="https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip">Flickr_8k_text </a></code>
- Rename the folder into **data**
- Make a **Glove** folder and dwonload the following links : <code><a href="https://www.kaggle.com/datasets/watts2/glove6b50dtxt">glove6b50dtxt </a></code> &nbsp;
<code><a href="https://www.kaggle.com/datasets/incorpes/glove6b200d">glove6b200d </a></code>
- Rename the folder into **GloVE**

## Python supported versions
The code is ready to run for every version of python greater than 3.6.
As you will see also in the code, some facilities are not available in python versions lower than 3.9.

## How this model works
Example <br>

<img src="photos/plane.jpeg" width=500>

caption generated for this image is,
```
a plane is flying in blue sky .
``` 
