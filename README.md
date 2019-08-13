# Yelp Humor Detection
This repository contains an exploration of recurrent neural networks (RNNs) and how they can be trained to detect humor. The [Yelp Open Dataset](https://www.yelp.com/dataset) is used for training and demonstration. The machine learning model is built with the help of [PyTorch](https://pytorch.org) and [spaCy](https://spacy.io/).

## How to view
Open `yelp_humor_detection.ipynb` in GitHub. If you want to view the notebook locally, install [Conda](https://conda.io) and Jupyter with [this guide](https://jupyter.readthedocs.io/en/latest/install.html#installing-jupyter-using-anaconda-and-conda). Then run:

```
$ jupyter notebook yelp_humor_detection.ipynb
```

and follow the initial instructions inside. These directions have been tested on macOS Mojave.

## How to run
If you want to train the model yourself, grab the dataset from [Yelp](https://www.yelp.com/dataset) and store the reviews JSON file (named `review.json`) in a new folder called `yelp_dataset` within the working directory before running through the notebook.
