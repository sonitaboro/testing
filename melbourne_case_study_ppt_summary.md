# Melbourne House Prices: PPT Summary

## Slide 1: Title
- Melbourne House Prices
- Exploratory Data Analysis and Data Preparation

## Slide 2: Dataset Overview
- 4,766 rows and 10 columns
- Mix of numeric and categorical predictors
- Main objective: explore house price drivers and prepare the dataset for predictive modelling

## Slide 3: Data Quality Findings
- No blank values
- No exact duplicate rows
- 17.33% of rows have Landsize = 0
- Small number of zero values in Bathroom and Bedroom
- Several suspicious records needed preparation handling

## Slide 4: Key EDA Insights
- Price is heavily right-skewed
- Log transformation makes the target more model-friendly
- Houses are the dominant property type
- Southern Metropolitan is the most expensive region
- Room count is the strongest numeric price signal

## Slide 5: Data Preparation
- Treated suspicious zero values as missing-like entries
- Added missing-value indicator flags
- Applied median imputation
- Used percentile clipping for outliers
- Used robust scaling and one-hot encoding

## Slide 6: Final Output
- Created a modelling-ready dataset file
- Recommended next models: Linear Regression, Random Forest, Gradient Boosting
- Dataset is ready for predictive modelling
