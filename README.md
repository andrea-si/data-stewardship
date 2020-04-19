# Project Title

The goal of this project was to examine nutritional data of various foods. The outcome of this project is helpful for people with special dietary needs, to make decisions on which food group should be consumed together, which food categories should be avoided.
This assignment consisted of three tasks; clustering, finding correlations between attributes of various foods, and comparing various food categories. Magnesium and calcium, when ingested at the same time, might negatively affect absorption of one another by our bodies. For example, for people who require a higher daily intake of magnesium, it is also important to not consume it with large amounts of calcium. Therefore, for the first task, the data is clustered based on these two attributes. A dataset labeling each food with the cluster number it belongs to is produced. In the second task, we examine how are various nutrients correlated with one another. Lastly, in the third task, we compare three pairs of categories on all their attributes. Several visualizations and csv files are produced as the output of this project.

### Prerequisites

In order to run the notebook, you will need to have following tools and libraries installed:

```
python 3.7.3
jupyter Notebook 6.0.2

pandas 0.25.3
numpy 1.17.4
scikit-learn 0.22

matplotlib 3.1.1
seaborn 0.9.0
```

### Data

The original input data used was the USDA Nutrient Dataset by U.S. Department of Agriculture, Agricultural Research Service. FoodData Central, 2019 https://fdc.nal.usda.gov/index.html

```
USDA_Food_Database.csv
```
The other 4 csv files were created as an output of a university project. They contain:
descriptive statistics about 36 food categories
```
categories.descriptive.csv
```

a correlation matrix showing correlation between various attributes of food categories
```
corr_matrix.csv
```
a result of K-means clustering in which a cluster number was assigned to each food item

```
clustered_food.csv
```

and lastly mean values of magnesium and calcium content of each food category.

```
mag_cal_per_category.csv

```


## Plots

Plots produced by the code in the Jupyter Notebook were saved in a png format.

## Running the project

To run this project, you will need to run the jupyter notebook
```
Project_nutrition.ipynb

```


## Authors

* **Andrea Siposova** - (https://github.com/andrea-si)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

