# myproject

## **by Michael Curley**

![Palmer Penguins](https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png)

## Table of Contents.

* [Introduction](#Introduction)
* [Dataset Columns](#dataset-columns)
* [Variable Classification](#variable-classification)

### ***Introduction***

This repository contains the Palmer Penguins dataset and Python code for analyzing it using a variety of Python software modules such as [pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/) and [Matplotlib](https://matplotlib.org/).

The Palmer Penguins dataset is a very popular dataset for data analysis and visualization tasks. It contains data on three different Penguin species collected on three islands in the Palmer Archipelago, in the Antartica region. The data was collected by Allison Horst, Alison Hill and Dr. Kristen Gorman between 2007 and 2009, and includes measurements such as bill length, bill depth, flipper length, body mass and species information for the Adelie, Chinstrap, and Gentoo penguins which were observed in these regions between the aforementioned dates.

### ***Dataset Columns***

- **species**: Penguin species (Adelie, Chinstrap, Gentoo)
- **island**: Island name (Biscoe, Dream, Torgersen)
- **bill_length_mm**: Length of the bill in millimeters
- **bill_depth_mm**: Depth of the bill in millimeters
- **flipper_length_mm**: Length of the flipper in millimeters
- **body_mass_g**: Body mass of Penguins in grams
- **sex**: Sex of the Penguins (male, female)


### ***Variable Classification***

For efficient data handling and modleling in Python, it is imperitive to choose the correct variable types to represent the various datasets we are modeling. Numerical data types can be represented using Pythons built in native data types while categorical variables are best represented as categorical data types in pandas for memory efficiency and best performance.

1. **Species**: The variety of species column is a categorical variable, as it represents different classes or categories of Penguins. There is no inherent ranking or order among the species and therefore the scale is **nominal**

1. **Island**: The island column is also a categorical variable

1. **bill_lenght**: The bill length is a numerical variable as it represents a measurable quality with a meaningful zero point. The scale type is **ratio** as they have a true zero point and no negative values. The ratios between values are meaningful, so if one observation has a value twice as large as another, then it means that the quanity being measured is also twice as large.

1. **bill_depth**: The bill depth is a numerical variable as it represents a measurable quality with a meaningful zero point. The scale type is **ratio** as they have a true zero point and no negative values. The ratios between values are meaningful, so if one observation has a value twice as large as another, then it means that the quanity being measured is also twice as large.


<p style="background:black">
<code style="background:black;color:white">C:\Users\Mike> pip3 install roughviz</code>
</p>