# Cardio EDA Analysis

Exploratory Data Analysis (EDA) of a cardiovascular disease dataset. The analysis identifies patterns and insights related to cardiovascular disease risk factors using patient health indicators such as age, blood pressure, cholesterol, and lifestyle habits.

## Project structure

```
Cardio_EDA_Analysis/
├── cardio-eda-analysis/
│   ├── data/
│   │   └── cardio_train.csv
│   └── notebook/
│       ├── cardio_eda.ipynb
│       └── cardio_cleaned.csv
└── README.md
```

## Dataset

- **Source:** `data/cardio_train.csv`
- **Size:** 70,000 records, 13 features
- **Features:** id, age, gender, height, weight, ap_hi, ap_lo, cholesterol, gluc, smoke, alco, active, cardio (target)

## Analysis overview

The notebook walks through:

1. Load dataset and libraries  
2. Dataset overview (shape, types, summary stats)  
3. Missing value and duplicate checks  
4. Feature engineering and column cleanup  
5. Outlier and unrealistic value handling  
6. Univariate and categorical analysis  
7. Correlation matrix and feature–cardio relationships  
8. Key insights  

## Requirements

- Python 3  
- pandas  
- numpy  
- matplotlib  
- seaborn  

Install with: `pip install pandas numpy matplotlib seaborn`

## How to run

1. Put `cardio_train.csv` in `cardio-eda-analysis/data/`.
2. Open `cardio-eda-analysis/notebook/cardio_eda.ipynb` in Jupyter.
3. Update the CSV path in the notebook if your paths differ (e.g. the first cell that loads the data).
4. Run all cells.

## Author

Thimira Kalansooriya
