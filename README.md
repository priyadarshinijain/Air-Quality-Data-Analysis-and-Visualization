# Air-Quality-Data-Analysis-and-Visualization

## 📖 Project Overview

This project provides a comprehensive analysis and visualization of air quality data. The dataset includes crucial air pollution metrics such as *PM2.5, **PM10, **SO2, **NO2, **CO, and **O3, along with meteorological factors like **temperature* and *pressure*. The goal is to explore these metrics and visualize trends to gain insights into air quality variations over time.

## 📂 Repository Structure

- *[Air_quality_visualization.ipynb](Air_quality_visualization.ipynb)*: 
  - This notebook loads, explores, and visualizes air quality data using Python libraries such as pandas, numpy, and seaborn.
  
- *[Air_quality_EDA.ipynb](Air_quality_EDA.ipynb)*: 
  - Focuses on *Exploratory Data Analysis (EDA)* to uncover statistical relationships and trends in the data using visualizations.

- *[air_quality_csv.ipynb](air_quality_csv.ipynb)*: 
  - Performs initial inspections of the dataset, such as data type checks and summarizing the structure of the data.

## ⚙️ Installation

To get started with this project, follow these steps:

bash
git clone https://github.com/your_username/your_repository_name.git
pip install -r requirements.txt



## 🌍 Air Quality & Meteorological Data Analysis

This project focuses on exploring and visualizing various air quality and meteorological variables, providing insights into pollution levels over time and across different locations.

## 🚀 Getting Started

To get started, open any of the notebooks in *Jupyter Notebook, **Google Colab*, or any Python IDE that supports .ipynb files. You can run the cells to load, explore, and visualize the dataset.

### 📦 Prerequisites
Ensure you have the following dependencies installed:
- pandas
- matplotlib
- seaborn
- numpy

You can install them using:
bash
pip install pandas matplotlib seaborn numpy

## 📊 Data Overview

The dataset consists of multiple air quality and meteorological variables, including:

| Pollutant | Description |
| --------- | ----------- |
| *PM2.5* | Particulate matter smaller than 2.5 microns |
| *PM10*  | Particulate matter smaller than 10 microns |
| *SO2*   | Sulfur dioxide levels |
| *NO2*   | Nitrogen dioxide levels |
| *CO*    | Carbon monoxide levels |
| *O3*    | Ozone levels |
| *TEMP*  | Temperature |
| *PRES*  | Atmospheric pressure |

The data is sourced from various air quality monitoring systems and is preprocessed in the notebooks for analysis.

## 📈 Visualizations

The notebooks produce a variety of visualizations to provide insights into the air quality metrics:

- *Time Series Plots*: Visualize how pollutant levels fluctuate over time.
- *Heatmaps*: Show correlations between different pollutants and meteorological variables.
- *Bar Charts & Line Graphs*: Compare pollutant levels and trends across locations or periods.

### Sample Visualization:

Relationship of two features using scatter plot

![image](https://github.com/user-attachments/assets/bdac52ec-5f40-4503-89ff-f93137f6d6ce)

Here's what we can interpret from this plot:

Temperature Range: The temperature ranges from about -10 degrees to over 40 degrees Celsius.

Pressure Range: The pressure ranges from below 1000 millibars to around 1040 millibars.

Trend: The plot shows a trend where pressure generally decreases as temperature increases. This inverse relationship is typical in atmospheric studies where warmer air tends to be less dense and thus exerts less pressure.

