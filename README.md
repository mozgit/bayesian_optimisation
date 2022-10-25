# README

## Intro

This repository contains starter set for research of the new startegies of Bayessian Optimisation.

## Setup

To prepare the workspace, you need to create an environment:

> conda env create -n hackaton python=3.10.7
> conda activate hackaton
> conda install botorch -c pytorch -c gpytorch -c conda-forge
> conda install pip
> conda install ipykernel
> python -m ipykernel install --user --name hackaton --display-name "BO_starterkit"
> pip install notebook
> pip install pandas
> pip install matplotlib
> pip install benchmark-functions

After this, you may start juptyer notebook:

> jupyter notebook

## How to start

The repository contains several notebooks allowing to focus on certain part of experimental design with Bayesian Optimisation.

 - Example 1 showcase fitting training data and generating suggestions out of it. It contains useful visualisations for all steps of the process. This is your place to go if you want to play with the most basic elements of the process - models and acquisition functions.
 - Example 2 shows iterative experimental design in action. It shows what points are chosen for testing. The notebook could be usefull to see how your changes of the BO affect the behaviour of the algorithm. Moreover, this notebook shows how to use benchmark functions from [benchmark-functions](https://gitlab.com/luca.baronti/python_benchmark_functions) library.
 - Example 3 shows how to run benhcmark for a selected function. This notebook could be usefull to test performance of your model and maybe compare it with others.

Consider existing notebooks as an introdiction material to bayesian optimisation and collection of snippets.