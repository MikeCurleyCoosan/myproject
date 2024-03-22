# myproject

## **by Michael Curley**

![Palmer Penguins](https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png)

<a target="_blank" href="https://docs.python.org/3/tutorial/index.html">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/> </a>
<a target="_blank" href="https://www.anaconda.com/">
  <img src="https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white" alt="Anaconda"/>
</a>
<a target="_blank" href="https://numpy.org/devdocs/index.html">
  <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
</a>
<a target="_blank" href="https://pypi.org/project/pandas/">
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
</a>
<a target="_blank" href="https://matplotlib.org/">
  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" alt="Matplotlib"/>
</a>
<a target="_blank" href="https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax">
  <img src="https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown"/>
</a>
<a target="_blank" href="https://www.latex-project.org/">
  <img src="https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX"/>
</a>
<a target="_blank" href="https://code.visualstudio.com/">
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Visual Studio Code"/>
</a>
<a target="_blank" href="https://jupyter.org/">
  <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
</a>

## Table of Contents.

* [About this project](#about-this-project)
* [Use of this project](#use-of-this-project)
* [Get Started](#get-started)
* [Get Help](#get-help)
* [Contribute](#contribute)
* [Author](#author)

### ***About this project***

This repository contains the Palmer Penguins dataset and Python code for analysing it using a variety of Python software modules such as [pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/) and [Matplotlib](https://matplotlib.org/).

The Palmer Penguins dataset is a very popular dataset for data analysis and visualization tasks. It contains data on three different Penguin species collected on three islands in the Palmer Archipelago, in the Antarctica region. The data was collected by Allison Horst, Alison Hill and Dr. Kristen Gorman between 2007 and 2009, and includes measurements such as bill length, bill depth, flipper length, body mass and species information for the Adelie, Chinstrap, and Gentoo penguins which were observed in these regions between the aforementioned dates. 

According to [Allison Horst GitHub](https://github.com/allisonhorst/palmerpenguins/blob/main/README.md) "the goal of the palmerpenguins is to provide a great dataset for data exploration and visualization, as an alternative to iris".

### ***Dataset Columns***

- **species**: Penguin species (Adelie, Chinstrap, Gentoo)
- **island**: Island name (Biscoe, Dream, Torgersen)
- **bill_length_mm**: Length of the bill in millimetres
- **bill_depth_mm**: Depth of the bill in millimetres
- **flipper_length_mm**: Length of the flipper in millimetres
- **body_mass_g**: Body mass of Penguins in grams
- **sex**: Sex of the Penguins (male, female)


### ***Variable Classification***

For efficient data handling and modlelling in Python, it is imperative to choose the correct variable types to represent the various datasets we are modelling. Numerical data types can be represented using Pythons built in native data types while categorical variables are best represented as categorical data types in pandas for memory efficiency and best performance.

1. **Species**: The variety of species column is a categorical variable, as it represents different classes or categories of Penguins. There is no inherent ranking or order among the species and therefore the scale is **nominal**

1. **Island**: The island column is also a categorical variable, as it represents places which have no inherent ranking or order which means the scale here is also **nominal**

1. **bill_length**: The bill length is a numerical variable as it represents a measurable quality with a meaningful zero point. The scale type is **ratio** as they have a true zero point and no negative values. The ratios between values are meaningful, so if one observation has a value twice as large as another, then it means that the quantity being measured is also twice as large.

1. **bill_depth**: The bill depth is a numerical variable as it represents a measurable quality with a meaningful zero point. The scale type is **ratio** as they have a true zero point and no negative values. The ratios between values are meaningful, so if one observation has a value twice as large as another, then it means that the quantity being measured is also twice as large.

1. **flipper_length**: The flipper length is again a numerical variable. Again, the scale type is **ratio** for the same reasons as given above for bill length and bill depth.

1. **body_mass**

### Use of this Project

Why the project is useful

### Get Started

#### To get stated with this project please follow these steps:

1. - Clone the repository to your local machine. 

'''sh
git clone https://github.com/MikeCurleyCoosan/myproject.git
'''

I used [Open in Colab](https://openincolab.com/) to generate the following clickable link. It opens the 'penguins.ipynb' notebooks in [Google Colab](https://colab.research.google.com/). This is the quickest way to get started using this project.

<a target="_blank" href="https://colab.research.google.com/github/MikeCurleyCoosan/myproject/blob/main/penguins.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



### Get Help

Where users can get help with your project

### Contribute 

Who maintains and contributes to the project

### Author

About me....



