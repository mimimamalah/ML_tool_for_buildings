# ML-powered Tool for assisted design of Buildings 

This project was developed as part of the EPFL Machine Learning course (2023).

## Authors
- Malak Lahlou Nabil
- Sara Anejjar
- Antoine Schutz

## Summary
This repository contains code used for a Machine Learning for Science project : ML-powered Tool for assisted design of Buildings .
It focuses on automating the labor-intensive and resource-demanding process of building design.The tool aims to leverage ML to predict structural specifications and safety evaluations from basic architectural and location-based data of
200 buildings.


### File description
```

├── Files 
│   ├── Raw_Files                    : Contains The Raw Excel files provided by the lab
│   ├── Before_Feature_Engineering   : Contains data generated by Data_Pre_Processing notebook
│   ├── After_Feature_Engineering    : Contains data generated by Feature_engineering notebook
│   ├── Visualisation                : Contains data generated by Visualization.ipynb


- DatabaseGuidelines.pdf : Project details provided by the lab

- my_dir : Contains Tuner Information for Hyperparameter Tuning for the Neural Networks

- Data_Pre_Processing.ipynb : Extract the data from Excel Files, Create Clean csv

- Feature_Engineering.ipynb : Use the dataset created in Data_Pre_Processing and perform feature engineering ( one Hot encoding , Scaling , removing 0 var , ...)

- Split_the_data.ipynb : Split the data into Test and training set for model Tuning

- Visualization.ipynb : Used to create Visualization during the Exploratory data Analysis 

- Run_Classical_ML_methods.ipynb : Create models using "Classical" Ml methods

- Run_Neural_Networks.ipynb : Neural networks 
```



## Requirements
- Python 3
  - `numpy`
  - `pandas`
  - `sklearn`
  - `keras`
  - `matplotlib` and `seaborn`
  
## Usage


To Create Our ML models , run the following files 

```
Data_Pre_Processing.ipynb                  :(The output of Data_pre_Processing is already stored in Files/Before_Feature_Engineering)
Split_the_data.ipynb                       :(The output of Split_the_data is already stored in both Files/After_Feature_Engineering and Files/Before_Feature_Engineering)
Feature_Engineering.ipynb                  :(The output of Data_pre_Processing is already stored in Files/After_Feature_Engineering)
Run_Classical_ML_methods.ipynb
Run_Neural_Networks.ipynb
```


