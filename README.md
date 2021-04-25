# data-science-python

This repository contains Jupyter notebooks from data science projects covering the following areas:

- NLP / text analysis / web & network science
  - [SherlockHolmsNetworks.ipynb](https://github.com/tphu06/data-science-python/blob/main/SherlockHolmsNetworks.ipynb)
- Machine learning using scikit-learn and TensorFlow
  - [neural_networks_project.ipynb](http://github.com/tphu06/data-science-python/blob/main/neural_networks_project.ipynb)
  - [unsupervised_learning_project.ipynb](https://github.com/tphu06/data-science-python/blob/main/unsupervised_learning_project.ipynb)
- Data analysis using Python
  - [Wine reviews.ipynb](https://github.com/tphu06/data-science-python/blob/main/Wine%20reviews.ipynb)

## SherlockHolmsNetworks.ipynb
In the four novels A Study In Scarlet, The Hound of the Baskervilles, The Valley of Fear, and The Sign of the Four by author Arthur Conan Doyle, private detective Sherlock Holmes is a recurring main character who tackles investigative cases for a wide range of clients. In this project we use text and network analysis methods to understand how character and location relationships in each novel are captured using these methods. In particular, sentential co-occurrence of character, location, and event entities is the focus of this project.

#### Required packages
- nltk
- spacy
- pygraphviz
- networkx
- wordcloud
- matplotlib
- textblob
- time
- urllib
- collections
- string
- pathlib
- inflect
- warnings

#### Input files
Txt files of four Sir Arthur Conan Doyle novels downloaded from [ProjectGutenberg](https://www.gutenberg.org/):
- baskervilles.txt: [The Hound of the Baservilles](https://www.gutenberg.org/ebooks/3070)
- scarlet.txt: [A Study in Scarlet](https://www.gutenberg.org/ebooks/244)
- sign.txt: [The Sign of the Four](https://www.gutenberg.org/ebooks/2097)
- valley.txt: [The Valley of Fear](https://www.gutenberg.org/ebooks/3289)

#### Outputs
Images in notebook.

## neural_networks_project.ipynb

#### Required packages
- tensorflow
- sklearn
- numpy
- pandas
- matplotlib
- scipy
- graphviz
- pydot
- time
- functools
- random

#### Input files
MNIST dataset - installed through API in notebook

#### Outputs
28 pdf images - see outputs in neural_networks_image_outputs.zip folder

| | | | |
|---|---|---|---|
| combined_frame | fivefour_frame |fourhundred_frame|hexsquared_frame|
|longcent_frame|overfitting_view_scatter|overfitting_x_depth_scatter|overfitting_x_neurons_scatter|
|plotting_frame|regression_plane_scatter|thousand_frame|time_view_scatter|
|time_x_depth_scatter|time_x_neurons_scatter|elu_demo_plot|leaky_relu_demo_plot|
|relu_demo_plot| selu_demo_plot|sigmoid_demo_plot|tanh_demo_plot|
|1_layers_120_tanh_cm|1_layers_120_tanh_standard_cm|mlp_best_cm|mlp_best_standard_cm|
|tf_basic_cm|tf_basic_standard_cm|1_layers_120_tanh|time_pie|

## unsupervised_learning_project.ipynb
#### Required packages
#### Input files
#### Outputs

## Wine reviews.ipynb
#### Required packages
#### Input files
#### Outputs
