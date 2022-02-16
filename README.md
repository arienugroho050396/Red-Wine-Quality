# Red-Wine-Quality :wine_glass:

[*here you can download the cheatsheet*](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)

## Introduction
Most wines are made with grapes, but they're not like the ones you find in the grocery store. Wine grapes (Latin name: Vitis vinifera) are smaller, sweeter, have thick skins, and contain seeds. According to wine folly, over 1,300 wine grape varieties are used in commercial production, but only about 100 of these varieties make up 75% of the world's vineyards. Wine is an alcoholic drink that is made up of fermented grapes. If you have come across wine, you will notice that wine also has its types. There are red wines, white wines. This was because of different varieties of grapes.

We can use machine learning in production process to ensure that every wine bottle has the highest quality. This will reduce the cost with regard to each wine bottle as less human labor is required for monitoring quality. Therefore, this analysis is aimed at predicting wine quality, given some important attributes in wine.

## Technical
- Language : Python (filetype: *.ipynb*)
- Library :
  - Matplotlib 
  - Seaborn

## Content
- **Fixed Acidity** — The amount of tartaric acid in wine (g/dm3).
- **Volatile Acidity** — The amount of acetic acid in wine (g/dm3).
- **Citric Acid** — The amount of citric acid in wine(g/dm3).
- **Residual Sugar** — The amount of sugar remaining after fermentation stops (g/dm3).
- **Chlorides** — The amount of salt in the wine (g/dm3).
- **Free Sulfur Dioxide** — The amount of sulfur dioxide (SO2) in free form (g/dm3).
- **Total Sulfur Dioxide** — The total amount of SO2 in the wine (g/dm3).
- **Density** — The density of water.
- **PH Value** — pH scale value.
- **Sulfites** — The amount of sulfites in the wine (g/dm3).
- **Alcohol** — The percent alcohol content of the wine.
- **Quality** — The quality of the wine, which is ranged from 1 to 10.

## Step Inside The Program
- **Exploratory Data Analysis**
- **Machine Learning Model**

## Conclusion
- All features have shown an effect on the quality of the wine. When the correlation of each variable is considered, we can see that some features are correlated to each other. This is because features such as fixed acid, citric acids are part of features like pH value. The major findings are that acidity has had a major effect in determining the quality of the wine. Also, consumers have stated that a high-quality wine should not contain an excess of residual sugars. This means a very sweet wine is not a feature of high-quality wine. The increase in alcohol level has also been viewed as a feature of good wine but, it should not increase to an amount where the wine will be categorized as hard liquor.
- from machine learning models we got stacking classifier and random forest classifier have higher perfromance than other models. stacking classifier is the one with highest accuracy 85.94%. We can see that without resampling there is a slight increase in accuracy. hence the model without SMOTE resampling is the best one. The accuracy can be increased by tuning hyper parameters of these models using scikit learn randomized grid search.

## [Click Here  for Visualize and Analyze](https://arienugroho050396.github.io/project4.html) :thumbsup: :thumbsup: :thumbsup: 
