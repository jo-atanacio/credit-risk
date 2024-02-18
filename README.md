# Credit Risk Modeling using Machine Learning

## Aim:
The main aim of the project is to learn about Credit Risk Modeling by predicting different parameters: Probabilty of Default (PD), Loss Given Default (LGD) and Expected Loss (EL). This will be achieve by using supervised machine learning in Python.

The equation for EL is given as:

** EL = PD x LGD x Loan Amount*

Once we have the probabilties of default we will then model Expected Loss using an assumed LGD of 1 (a LGD of 1 is a conservative assumption given the unsecured nature of the loans) 

<pre>
├── Data
│    ├── LCDataDictionary.xlsx (List of all features of dataset)
│    ├── loan_data_07_18.csv
├── Notebooks
│    ├── eda_basic_processing.ipynb
│    ├── processing
│    ├── pd_processing.ipynb (Preprocessing for PD model)
│         ├── lgd_processing.ipynb (Preprocessing for LGD & EAG)
│    ├── modeling
│         ├── pd_modeling.ipynb (Modeling PD and Score card)
│         ├── lgd_modeling.ipynb (Modeling LGD & EAD i.e training models)
│         ├── expectedloss.ipynb (Calculating expected loss)
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