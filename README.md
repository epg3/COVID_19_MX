# Covid-19 Mexico

![](./images/Cover.jpg)

COVID-19 is taking a big toll on the Mexican population. Currently, it has the 6th place Coronavirus (COVID-19) cases worldwide. However, it has the Coronavirus (COVID-19) deaths worldwide (as per today Aug-11-2020). I decided to dive into the official data released by the Mexican authorities. 

## Table of Contents
- [Data](##Data)
- [Content](##Content)
- [Installation](##Installation)
- [Analysis](##Analysis)

## Data

COVID-19 data was taken from [Ministry of Health MX](https://www.gob.mx/salud/documentos/datosåabiertos-152127 )


Mexico's Shape File was taken from [ESRI](https://www.arcgis.com/home/item.html?id=ac9041c51b5c49c683fbfec61dc03ba8)

Population data was taken from [INEGI](https://www.inegi.org.mx/temas/estructura/) and [PopulationPyramid.net](https://www.populationpyramid.net/es/méxico/2020/)

## Contet

EDA.ipynb
Model.ipynb
Map.ipynb

## Installation
The file requirements.txt specifies all the libraries and dependencies for these notebooks.
Execute the command to install all necessary packages.

```shell
$ pip install requirements.txt
```
> **Note:** This project requieres Python 3 and Jupyter Notebook.

## Analysis

The main question is:
* Which factor has the biggest impact on deaths once infected with COVID-19?

Other questions to tackle are:
* Is there a correlation between cases and death with days of the week?
* Does the probability of death is increased by the number of days between first symptoms and hospitalization?
