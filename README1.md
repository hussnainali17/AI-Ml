# 1st Task: Iris Dataset Exploration

## Task Objective

The objective of this notebook ([1stTask.ipynb](1stTask.ipynb)) is to perform exploratory data analysis (EDA) and visualization on the Iris dataset. The goal is to understand the structure, distribution, and relationships between features and species in the dataset.

## Dataset Used

- **Iris Dataset**: Loaded using both `scikit-learn` (`load_iris()`) and `seaborn` (`sns.load_dataset("iris")`).
- The dataset contains 150 samples of iris flowers with the following features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
  - Species (setosa, versicolor, virginica)

## Models Applied

- No machine learning models are applied in this notebook.
- The focus is on data exploration and visualization using:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for plotting

## Key Results and Findings

- **Scatter Plots**: Visualized relationships between sepal length/width and petal length/width, colored by species.
- **Histograms**: Examined the distribution of each feature, revealing clear separation between species, especially in petal measurements.
- **Boxplots**: Compared petal length across species, showing distinct differences.
- **Summary Statistics**: Used `describe()` and `info()` to understand feature ranges and data types.

These visualizations confirm that the Iris dataset is well-structured and that species can be visually separated based on petal measurements.

---
```# 1st Task: Iris Dataset Exploration

## Task Objective

The objective of this notebook ([1stTask.ipynb](1stTask.ipynb)) is to perform exploratory data analysis (EDA) and visualization on the Iris dataset. The goal is to understand the structure, distribution, and relationships between features and species in the dataset.

## Dataset Used

- **Iris Dataset**: Loaded using both `scikit-learn` (`load_iris()`) and `seaborn` (`sns.load_dataset("iris")`).
- The dataset contains 150 samples of iris flowers with the following features:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
  - Species (setosa, versicolor, virginica)

## Models Applied

- No machine learning models are applied in this notebook.
- The focus is on data exploration and visualization using:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for plotting

## Key Results and Findings

- **Scatter Plots**: Visualized relationships between sepal length/width and petal length/width, colored by species.
- **Histograms**: Examined the distribution of each feature, revealing clear separation between species, especially in petal measurements.
- **Boxplots**: Compared petal length across species, showing distinct differences.
- **Summary Statistics**: Used `describe()` and `info()` to understand feature ranges and data types.

These visualizations confirm that the Iris dataset is well-structured and that species can be visually separated based on petal measurements.
