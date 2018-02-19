# LinkedBooksDeepReferenceParsing

TBD

## TODO

Giovanni

*	Add dataset to repo and update this file (remove the not used annotation scheme, position 3 in a split)
*	How to share pretrained vectrs? is it worth it? Zenodo is an option.
*   Paper writing
*   Tensorflow code
*   Check everything

Danny

*   ~~Create high-res (vector) figures (and fix the fontsize of some of them!)~~
*   ~~Check paper as I write, I am adding small TODOs there!~~
*   ~~Prepare a data analysis notebook with a selection of results (esp. from 0. Data Analysis, Appendix C)~~
*   ~~Push (in a separate branch) the clean Keras code (for single and multi task)~~
*   ~~Add info on how to use it in the README~~
*   Provide some more on error analysis (examples of miss-classified instances, etc.). TO BE DISCUSSED first
*   ~~Code cleanup~~
*   Tests with learning rate and multi-task fine-tune
*   Improve Keras readme ? GIOVANNI ?
*   ~~Neural ParsCit~~

## Task

## Dataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1175213.svg)](https://doi.org/10.5281/zenodo.1175213)

## Implementations

### CRF baseline

### Keras

The directory contains code to run the models with a Keras implementation. Code for both single and multitask models are given. For the single tasks, one model for each of the three tasks will be computed by running the python script *main_threeTasks.py*. The multitask learning model can be computed with the script *main_multiTaskLearning.py*.

The data is expected to be in a *data* folder, one directory up, with three files inside it: *train.txt* for the training dataset, *test.txt* for the testing dataset, and *valid.txt* for the validation dataset.

The results will be stored into the *model_results* folder, with one directory created for each model.

### Tensor Flow








