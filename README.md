# TDA-Spring2025

This repository contains code and other material for the course *CS 7870, Seminar in Theoretical Computer Science: Topological Methods for the Analysis of Data*.

## Installing Python:
Get Python installed in your machine. I suggest using the latest Anaconda distribution: https://www.anaconda.com/products/distribution


## Clone the repository:

Please install git on your machine by following the directions in 

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Clone the github repository using git: **Open a terminal (Linux/mac) | an Anaconda Powsershell Prompt (Windows)** and run
```
git clone https://github.com/joperea/TDA-Spring2025.git
```


## Create and activate the course's conda environment:

We will first create and activate a separate conda environment for the course. This is so we don't create conflicts with any other packages in your Python installation. 
```
conda create -n TDA python=3.9
conda activate TDA
```

## Install dependencies:
#### Homework 1
```
pip install glasbey scikit-learn jupyterlab
```
#### Clustering (Demo 1):
```
pip install pandas
pip install git+https://github.com/LuisScoccola/persistable.git@experimental
```

#### Euler Curves (Demo 2):
```
pip install bokeh pymeshlab hirola
```

#### Computing persistent homology (Demo 3):
```
pip install cython ripser plotly
```
