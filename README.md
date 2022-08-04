# 52954 - Machine Learning & Statistics Project | Leonard Curtin

The following repository contains two jupyter notebooks that were created as part of the assessment process for a machine learning and statistics module.

## Jupyter notebook files
---

### scikit-learn.ipynb
This notebook provides a brief introduction into the domain of machine learning and an overview of the scikit-learn python library.

Utilising scikit-learn working examples of the supervised machine learning tasks of **classification** and **regression** are contained within.

Prior to these tasks **exploratory data analysis** (EDA) takes place for each dataset examined.

---

### anova.ipynb
This notebook provides a working example of a one-way ANOVA (analysis of variance) being conducted on a dataset.

A hypothesis is firstly established, followed by the dataset being tested on a series of *assumptions*, in order to ensure that the data can be analysed by using a one-way ANOVA.

A one-way ANOVA is then conducted utilising the python libraries of:  
* scipy.stats
* statsmodels

Prior to these tasks **exploratory data analysis** (EDA) takes place on the dataset examined.


## Running the project files
The programming language of **Python** was utilised for this project.  

For ease of access I would recommend installing Python using the **Anaconda distribution**.  

### The following packages are required in order to successfully run this project.
* Jupyter (Jupyter lab/jupyter notebook)
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Statsmodels

If utilising Anaconda these packages can be installed by entering the following code within the Anaconda prompt:  

conda install (insert package name) 

## Regarding the Datasets
The datasets that come preloaded with scikit-learn were analysed throughout this project i.e., the toy datasets. *See sample code below*.

```python
#Importing our dataset for regression
from sklearn.datasets import load_diabetes
```





