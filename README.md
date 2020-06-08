# ANALYSIS OF TEMPERATURES IN SPAIN SINCE 1950

This project analyze the temperatures in Spain in the last decades. With this objective we will apply data analysis and information visualization.

We will get the data from the AEMET OpenData API. You can check it on http://www.aemet.es/es/datos_abiertos/AEMET_OpenData, a website that provides weather data of meteorological stations located in different points of Spain.

In order to see if there has been a change in the evolution of temperatures in recent years, we will separate the data in two periods. A period before year D and period after year D. Then, we will keep the maximum and minimum temperatures of each day of the year, for both of those periods. In this way we will be able to see if in the recent period the temperatures are significantly different or not.

Check the project in the jupyter notebook **global_warming.ipynb** or in this [link](https://htmlpreview.github.io/?https://github.com/Albert-GM/global_warming/blob/master/global_warming.html)!

## Want to install this project on your own machine?

Start by installing Anaconda (or Miniconda) and git.

Next, clone this project by opening a terminal and typing the following commands (do not type the first $ signs on each line, they just indicate that these are terminal commands):

```
$ git clone https://github.com/Albert-GM/global_warming.git
$ cd global_warming
```

Next, run the following commands:

```
$ conda env create -f environment.yml
$ conda activate global_warming
```
Finally, start Jupyter:

```
$ jupyter notebook
```
