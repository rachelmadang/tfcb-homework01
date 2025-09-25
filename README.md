# Description

This repository contains files that were once part of a `messy-project-directory`. These files have since been renamed and reorganized into the following subfolders:

* [`data`](#data)
* [`images`](#images)
* [`source_code`](#source-code)

Additional descriptions of contents can be found by scrolling below or by selecting above to skip to pertinent sections.

## Data

Contains data from the 2013 and 2014 field seasons.

> **Note**: Multiple versions are included in this repo. For those that demonstrate tidy data principles, see those with keyword *tidy* included in filename.

## Images

Contains images of ant specimens from the California Academy of Sciences Entomology department. For further reading on ants (or other insects and arachnids) please see [their website](https://www.calacademy.org/scientists/entomology) or try [Wikipedia](https://en.wikipedia.org/wiki/Entomology).

![](./images/casent0172345_rhytidoponera_metallica.jpg)

## Source code

| **Scripts** | **Description** |
|-----------|---------|
|`get_dataset.py`|Downloads a dataset|
|`get_species_list.py`|Creates a CSV file with species that are imaged the most from [AntWeb](https://www.antweb.org)|
|`main.py`|Initializes, trains and evaluates a model|
|`predict_images.py`|Loads and compiles model with trained weights to predict species from an image|
