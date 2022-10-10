#  Homework 1

Here are some details about the included subfolders and their contents.

## images

This folder includes photos of ants. Here is an example.

<img src="./images/casent_0172345_rhytidoponera_metallica.jpg" style="width:150px;"/> 

If you want to know more about ants, here is a [LINK](https://en.wikipedia.org/wiki/Ant) to the wikipedia article.

## source_code

This folder contains the following scripts:

- get_dataset.py provides functions for downloading and handling the datasets.
- get_species_list.py is a script to create a cdv file with the species that are imaged the most.
- main.py initializes the model and trains the model, after which training is evaluated and the model is tested.
- predict_image.py loads a model with trained weight and predicts an image or a test set.

## data

This folder includes a table. Tidy data should look like this.

| variable_a | variable_b | variable_c |
| ---------- | ---------- | ---------- | 
| obsv_01_a | obsv_01_b | obsv_01_c |
| obsv_02_a | obsv_02_b | obsv_02_c |