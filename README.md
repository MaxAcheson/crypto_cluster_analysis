# Analysis of Cryptocurrency Clusters

This analysis uses a cryptocurrency dataset in order to conduct PCA (principal component analysis) and data clustering. The goal is to detect and use an optimal KMeans value in order to identify patterns in the data.

## Technologies

This project utilizes python 3.7 and the following packages:

[jupyterlab](https://jupyter.org/)

[pandas](https://pandas.pydata.org/)

[pyviz](https://pyviz.org/)

[scikit-learn](https://scikit-learn.org/stable/index.html)

[holoviews](http://holoviews.org/)

The project has been constructed in a [Jupyter Lab](https://jupyter.org/) notebook entitled `crypto_investments.ipynb`.

## Installation Guide

To clone the repository to your computer, first make sure you are using python version 3.7 or greater by typing the following:

`python -V`

Next, confirm that the packages are installed by using the following code lines:

`pip install jupyterlab`

`pip install pandas`

`pip install pyviz`

`pip install scikit-learn`

`pip install hvplot`

## Usage

In order to view the project, navigate to the `crypto_investments.ipynb` notebook in the repository directory. If you cannot find the file, simply click [here](https://github.com/MaxAcheson/module_10_challenge/blob/main/Starter_Code/crypto_investments.ipynb) instead. If you would like to interact with the live version of the analysis, you may navigate to your cloned version of the repository in your terminal and run `jupyter lab`.

Since the analysis figures do not render live on GitHub, the figures from the analysis have been provided below, along with their corresponding notebook cell.

[Cell 11 Out]:
![inertia vs k market data](https://github.com/MaxAcheson/module_10_challenge/blob/main/Images/Inertia%20vs.%20k%20values.png)

[Cell 17 Out]:
![Clusters Part 1](https://github.com/MaxAcheson/module_10_challenge/blob/main/Images/Clusters%2024%20hour%20and%207%20day.png)

[Cell 26 Out]:
![inertia vs k PCA](https://github.com/MaxAcheson/module_10_challenge/blob/main/Images/Inertia%20vs.%20k%20PCA.png)

[Cell 30 Out]:
![Clusters Part 2](https://github.com/MaxAcheson/module_10_challenge/blob/main/Images/Clusters%2024%20hour%20and%207%20day%20PCA.png)

[Cell 31 Out]:
![Composite 1](https://github.com/MaxAcheson/module_10_challenge/blob/main/Images/Composite%20Plots%20Elbow.png)

[Cell 32 Out]:
![Composite 2](https://github.com/MaxAcheson/module_10_challenge/blob/main/Images/Composite%20Plots%20Clusters.png)

## Contributors

Max Acheson

maxacheson@gmail.com

[LinkedIn](https://www.linkedin.com/in/max-acheson-75093a19a/)

## Licenses

MIT License

Copyright (c) [2021] [Max Acheson]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
