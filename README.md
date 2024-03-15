# myproject

## **by Michael Curley**

![Palmer Penguins](https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png)



![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Table of Contents.

* [About this project](#about-this-project)
* [Dataset Columns](#dataset-columns)
* [Variable Classification](#variable-classification)

### ***About this project***

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

### Use of this Project

Why the project is useful

### Get Started

I used [Open in Colab](https://openincolab.com/) to generate the following clickable link. It opens the 'penguins.ipynb' notebooke in [Google Colab](https://colab.research.google.com/).

<a target="_blank" href="https://colab.research.google.com/github/MikeCurleyCoosan/myproject/blob/main/penguins.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

### Get Help

Where users can get help with your project

### Contribute 

Who maintains and contributes to the project

### Author

About me....

<p style="background:black">
<code style="background:black;color:white">C:\Users\Mike> pip3 install roughviz</code>
</p>