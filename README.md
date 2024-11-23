# Mental Health in Tech: HR Support Analysis

## Overview
Analysis of mental health survey data to support HR's pre-emptive mental health program. This project identifies employee clusters and provides actionable insights for targeted interventions.

## Business Context
The HR department is initiating a pre-emptive mental health program. This analysis aims to:
- Reduce complexity of high-dimensional survey data
- Identify distinct employee clusters
- Provide actionable insights for HR interventions
- Create interpretable visualizations

## Key Findings
### Cluster Analysis
1. Uncertain/Neutral Cluster (39.86%)
   - High uncertainty about benefits
   - Limited organizational resources
   - Low mental health prevalence

2. Supportive Environment Cluster (30.82%)
   - Strong mental health benefits
   - High resource availability
   - Positive leave policy perception

3. Limited Support Cluster (29.32%)
   - Limited organizational support
   - High negative consequences
   - Significant career concerns

## Project Structure
```
mental-health-tech/
├── data/                # Survey data files
│   └── survey_2016.csv
├── notebooks/          # Jupyter notebooks
│   └── Mental_Health_project.ipynb
├── requirements.txt    # Project dependencies
├── .gitignore         # Git ignore file
└── README.md          # Project documentation
```

## Setup
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter notebook: `jupyter notebook`

## Dependencies
- pandas==1.4.2
- numpy==1.22.3
- scikit-learn==1.0.2
- matplotlib==3.5.1
- seaborn==0.11.2

## Limitations
- Geographic bias (62.4% US-based)
- Gender imbalance (72.5% male)
- Self-reported data

## Visualizations
See `visualization_catalog.md` for a complete catalog of generated visualizations organized by category.