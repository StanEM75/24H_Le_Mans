# 24 Hours Le Mans - DataViz and Machine Learning

![Project Image](https://global.toyota/pages/news/images/2017/12/19/WEC/001.jpg)

## 🚀 Introduction

Since 2012, Toyota has been participating in the World Endurance Championship (WEC).<br><br>
This exceptional longevity has allowed the brand to progress year after year, culminating in winning 5 consecutive editions of the 24 Hours of Le Mans.<br><br>
By obtaining as many details as possible about each race in the championship in which Toyota has participated, our goal will be to create a predictive model for Toyota’s result at the end of the race: victory (one of the Toyotas in first place) or defeat otherwise.

## 🛠️ Technos Used

- **Python**
- **Scikit-Learn**
- **Pandas**
- **Matplotlib / Seaborn**

## 🔑 Projects 

1. **Process : Pre-Processing**
- Keep only the relevant cars (same category as Toyota).
- Data Format : Dates, Null.
- Keep Only the unique values for every column.

2. **Process : EDA**
- Victories of Toyota per Race, Year, Car and Type of Race.

3. **Process : Feature Engineering**
- Add new features regarding races or cars characteristics.

4. **Supervised Learning : Feature Engineering**
- Train the First Model: RandomForestClassifier.
- Check the correlation between variables.
- PCA analysis to standardize and reduce the dimensionality.
- Train xgBoost and SVC models.
- Check the results and export the best model with the transformations needed to get the correct output.
