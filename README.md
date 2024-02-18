# Credit Risk Modeling using Machine Learning

## Aim:
The main aim of the project is to learn about Credit Risk Modeling by predicting different parameters: Probabilty of Default (PD), and Loss Given Default (LGD). This will be achieve by using supervised machine learning in Python.

<pre>
├── Data
│    ├── working_data.parquet (Processed dataset)
│    ├── loan_data_07_18.csv (Download from Kaggle Source and add it here)
├── Notebooks
│    ├── eda.ipynb
│    ├── preprocess.ipynb 
│    ├── pd.ipynb (Probability of Default)
│    ├── lgd.ipynb (Loss Given Default)
</pre>

## Dataset:
The dataset contains all available data for more than 800,000 consumer loans issued from 2007 to 2018 by Lending Club: a large US peer-to-peer lending company.
Dataset: https://www.kaggle.com/datasets/wordsforthewise/lending-club/data
* Note: only using the accepted loan dataset.

## Models:
* For PD --> logistic regression
* For LGD -> Logistic Regression and Linear Regression
* For EAD -> linear regression

## Tools: pandas, scikit-learn, plotly, Flask
## Skills: Credit Risk, Machine Learning, Exploratory Analysis