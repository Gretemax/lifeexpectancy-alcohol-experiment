# Life Expectancy - Alcohol Consumption Analysis

## Description
This repository contains code for analyzing the correlations between average alcohol consumption and average life expectancy around the world.

## Files

The files have been organized into their respective categories. Files concerning alcohol consumption can be found at `data/alcohol-consumption-data/`, while files concerning life expectancy can be found at `data/life-expectancy-data/`.

### Alcohol Consumption
* `alcohol-consumption.csv`: Dataset of the average alcohol consumption around the world between the years 2000 to 2018, per country per capita. The alcohol consumption is measured in liters of pure alcohol per capita per year.
* `alcohol-consumption_meta.json`: Metadata describing the structure of `alcohol-consumption.csv` and its different fields.

### Life Expectancy
* `life-expectancy.csv`: Dataset of the average life expectancy around the world between the years 2000 to 2019. The life expectancy is measured in years.
* `life-expectancy_meta.json`: Metadata describing the structure of `life-expectancy.csv` and its different fields.

### Results
* `results.ipynb`: Jupyter Notebook calculating the correlation between average alcohol consumption and life expectancy around the world, and plotting various metrics and findings


## How to run the Experiment
In order, to run the provided Jupyter Notebook on Python 3.11, you will need the following:

1. **Python 3.11** installed on your machine. Python is the programming language used to run the experiment. You can download it from the official [Python website](https://www.python.org)
2. **Jypyter Notebook** installed on your machine. This is the environment used to house the experiment. You can download it from the [official website](https://jupyter.org) or by typing `pip install notebook jupyter`
3. **Required Libraries** installed on your machine. The experiment uses the Python libraries "Matplotlib", "Pandas", "CSV", and "NumPy", which can be installed by typing `pip install pandas numpy matplotlib csv` into the command line of your terminal (note that the command line should be located inside the experiment´s directory)
4. **Start the Jupyter Notebook** by typing `jupyter notebook` into your command line
5. **Get the Visualizations** by running the code (by pressing the play button on the top)

Please note that these exact steps may differ depending on your operating system and setup. 