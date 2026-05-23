\# Climate Analytics: Impact of Climate Change on Great Barrier Reef Tourism

\#\# Project Overview

This project analyzes the relationship between climate-related environmental stress indicators and tourism activity in the Great Barrier Reef region of Australia.

The main objective is to explore whether climate stress indicators, especially thermal-stress variables linked to coral bleaching, can help explain and predict tourism activity measured through overnight tourist trips.

This project was completed as part of a college climate analytics project.

\#\# Research Context

The Great Barrier Reef is one of the world's most important marine ecosystems and a major tourism destination. Climate change has increased environmental pressure on coral reefs through rising sea surface temperatures, coral bleaching, extreme weather events, and reduced water quality.

This project investigates how environmental stress indicators, together with economic indicators such as GDP and GSP, relate to tourism demand in the Great Barrier Reef region.

\#\# Key Questions

\- Which climate and environmental variables are associated with coral stress and reef degradation?  
\- Can climate-stress indicators help explain tourism activity in the Great Barrier Reef region?  
\- Which regression model performs best for predicting overnight tourist trips?  
\- How do economic indicators and thermal-stress indicators influence tourism prediction?

\#\# Tools and Technologies

\- Python  
\- Jupyter Notebook  
\- pandas  
\- NumPy  
\- scikit-learn  
\- matplotlib  
\- seaborn  
\- Excel  
\- Tableau  
\- Regression Modeling  
\- Data Visualization  
\- Predictive Analytics

\#\# Dataset Summary

The project uses climate-stress, coral bleaching, tourism, GDP, and GSP indicators from academic and statistical sources referenced in the final project report.

The combined dataset covers quarterly observations from 1998 to 2017\.

The raw and processed datasets are not included in this repository because redistribution permissions have not been fully verified.

\#\# Features Used for Modeling

The modeling workflow used environmental, climate, economic, and time-based features, including:

\- Quarter  
\- Average Turbidity  
\- Average Cyclone Frequency  
\- Average Climatological Sea Surface Temperature  
\- Average Sea Surface Temperature Anomaly  
\- SSTA Frequency  
\- SSTA Degree Heating Weeks  
\- Average Thermal Stress Anomaly  
\- TSA Frequency  
\- TSA Degree Heating Weeks  
\- Gross State Product  
\- Gross Domestic Product

The target variable was overnight tourist trips.

\#\# Methodology

The project workflow included:

1\. Data collection from climate, tourism, and economic sources  
2\. Data cleaning and integration  
3\. Quarterly aggregation of climate-stress indicators  
4\. Exploratory data visualization  
5\. Feature preprocessing  
6\. One-hot encoding for categorical quarter variables  
7\. Standard scaling for numerical variables  
8\. Regression model development  
9\. Model comparison using Mean Absolute Error  
10\. Interpretation of model coefficients and tourism impact

\#\# Models Compared

The following models were evaluated:

| Model | Mean Absolute Error |  
|---|---:|  
| Average Baseline Model | 405.84 |  
| Linear Regression with Forward Stepwise Selection | 180.97 |  
| Lasso Regression Degree 2 | 267.06 |  
| Lasso Regression Degree 1 | 260.24 |  
| Ridge Regression Degree 1 | 300.19 |

The best-performing model was Linear Regression with Forward Stepwise Feature Selection.

\#\# Key Findings

The best model selected GDP, GSP, and Average Thermal Stress Anomaly as important predictors.

The model results suggest that economic activity strongly influences tourism demand, while thermal-stress indicators provide additional information about climate-related pressure on tourism.

The findings should be interpreted as exploratory rather than causal because tourism demand is affected by many economic, environmental, and social factors.

\#\# Limitations

This project has several limitations:

\- The dataset contains only 61 quarterly observations.  
\- Tourism is measured using overnight trips, which may include non-reef-related tourism.  
\- Direct coral bleaching severity or coral cover loss was not available as a target variable.  
\- Economic indicators such as GDP and GSP may dominate climate-related effects.  
\- The analysis identifies associations but does not prove causality.

\#\# Future Work

Possible future improvements include:

\- Adding lagged climate and bleaching variables  
\- Using rolling-window or time-series cross-validation  
\- Including direct coral reef health indicators  
\- Applying causal impact analysis around major bleaching events  
\- Expanding the dataset with more recent observations

\#\# Repository Structure

\`\`\`text  
climate-tourism-analytics-great-barrier-reef/  
│  
├── notebooks/  
│   ├── README.md  
│   └── Model.ipynb  
│  
├── reports/  
│   ├── README.md  
│   └── Climate Analytics Project.pdf  
│  
├── presentation/  
│   ├── README.md  
│   └── Project Presentation.pptx  
│  
├── tableau/  
│   ├── README.md  
│   └── Coral Bleaching.twb  
│  
├── data/  
│   └── README.md  
│  
├── requirements.txt  
├── .gitignore  
└── README.md  
\`\`\`

\#\# How to Run the Notebook

1\. Clone the repository:

\`\`\`bash  
git clone https://github.com/praveenrajece2018-code/climate-tourism-analytics-great-barrier-reef.git  
\`\`\`

2\. Open the project folder:

\`\`\`bash  
cd climate-tourism-analytics-great-barrier-reef  
\`\`\`

3\. Install the required Python libraries:

\`\`\`bash  
pip install \-r requirements.txt  
\`\`\`

4\. Open Jupyter Notebook:

\`\`\`bash  
jupyter notebook  
\`\`\`

5\. Open the notebook inside the \`notebooks/\` folder.

\#\# Data Availability Note

The datasets are not included in this repository because redistribution permissions have not been fully verified.

To rerun the notebook, place the required dataset files inside the \`data/\` folder:

\- \`MetricsVisits\_new.csv\`  
\- \`MetricsVisits\_new\_expected.csv\`

The notebook uses relative file paths from the \`notebooks/\` folder to the \`data/\` folder.

\#\# Project Status

Completed as a college climate analytics project.

\#\# Author

Praveen Raj Balakrishnan    
M.Sc. Data Analytics and Decision Science    
RWTH Aachen University

\#\# License

The code and notebook structure in this repository can be licensed separately if required.

The project report, presentation, visualizations, datasets, and third-party source materials are provided for academic portfolio demonstration only and are not covered by an open-source license unless otherwise stated.

Raw and processed datasets are not included because redistribution permissions have not been fully verified.  
