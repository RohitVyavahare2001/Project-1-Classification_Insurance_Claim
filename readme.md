# Insurance Data Analysis Project

## Overview
This project analyzes insurance data to predict insurance claims and understand the relationships between various demographic and health factors with insurance charges. The analysis includes extensive exploratory data analysis (EDA), feature correlation studies, and predictive modeling.

## Dataset
The dataset (`insurance.csv`) contains information about insurance beneficiaries including:

| Feature | Description |
|---------|-------------|
| age | Age of policyholder |
| sex | Gender of policyholder (male(1)/female(0)) |
| bmi | Body mass index (kg/m²) |
| children | Number of children/dependents |
| smoker | Smoking status (nonsmoker(0)/smoker(1)) |
| region | Residential area (northeast(0)/northwest(1)/southeast(2)/southwest(3)) |
| charges | Medical costs |
| insuranceclaim | Claim status (yes(1)/no(0)) |

## Requirements
Required Python packages:
```bash
pip install -r Requirements.txt
```

## Analysis Components

### 1. Data Preprocessing
- Data loading and initial inspection
- Null value checking (no null values found)
- Basic statistical analysis
- Feature scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)

#### BMI Analysis
- Distribution analysis showing normal distribution
- BMI categorization:
  - Underweight: < 18.5
  - Normal weight: 18.5-24.9
  - Overweight: 25-29.9
  - Obese: ≥ 30
- Relationship studies with age, charges, and claims

#### Age Analysis
- Age distribution visualization
- Correlation with charges and children
- Insurance claim patterns across age groups
- Smoking habits across age groups

#### Smoking Status Analysis
- Impact on insurance charges
- Relationship with claims
- Distribution of smokers vs non-smokers

#### Regional Analysis
- Claim patterns across regions
- Distribution of policyholders by region

### 3. Key Findings

#### Demographic Insights
1. Higher insurance policy purchases among 18-20 year olds (2x more than other age groups)
2. Linear relationship between age and charges for some segments
3. Diverse age distribution for both smokers and non-smokers

#### Cost Factors
1. Smokers have significantly higher charges
2. More non-smokers in dataset, but smokers make more claims
3. Southeast region shows higher claim rates

#### Correlations
1. Negative correlation between children and claims
2. BMI correlates with claims
3. Smoker status, BMI, and charges show strongest correlation with insurance claims


## Getting Started
1. Clone this repository
2. Install required packages:
```bash
pip install -r Requirements.txt
```
3. Open the Jupyter notebook to access the full analysis

## Project Structure
```
├── insurance.csv          # Dataset
├── Project 1 - Classification.ipynb  # Main analysis notebook
└── Requirements.txt      # Package requirements
```


## Contact
www.linkedin.com/in/rohitvyavahare2001