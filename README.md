# Price-Recommendation-for-Online-Sellers

## Overview

This project focuses on helping online sellers set appropriate prices for their products. It employs three different regression models—Linear Regression, RandomForestRegressor, and XGBRegressor—to make price recommendations. Each model's performance is evaluated using the R2 score, providing insights into their effectiveness in price prediction.

## Table of Contents

1. [Introduction](#introduction)
2. [Models Used](#models-used)
3. [Usage](#usage)
4. [Dataset](#dataset)
5. [Results](#results)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

Pricing is a critical aspect of e-commerce. This project aims to assist online sellers in determining optimal prices for their products, ultimately improving their competitiveness and profitability.

## Models Used

Three regression models were utilized:

1. **Linear Regression:** Linear regression is known for its simplicity and interpretability. An R2 score of 0.844 suggests strong predictive performance.

2. **RandomForestRegressor:** RandomForestRegressor leverages decision trees and ensemble techniques. It achieved an R2 score of 0.216.

3. **XGBRegressor:** XGBoost is a gradient boosting algorithm that excels in predictive accuracy. It obtained an R2 score of 0.219.

## Usage

To use the price recommendation models:

1. Clone the repository: `git clone https://github.com/yourusername/price-recommendation.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis: `python price_recommendation.py`

You can customize the models and parameters as needed for your specific pricing needs.

## Dataset
Description : "This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

The dataset used for this project is located in the kaggle and the link is provided below. 

dataset --->>> https://www.kaggle.com/datasets/carrie1/ecommerce-data

## Results

- **Linear Regression**: The high R2 score (0.844) indicates that Linear Regression performs exceptionally well in price prediction, closely aligning with the actual prices.

- **RandomForestRegressor and XGBRegressor**: While the R2 scores for these models (0.216 and 0.219, respectively) are lower than Linear Regression, they still provide valuable insights into price trends and patterns.

## Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy
- xgboost (for XGBRegressor)
- matplotlib (for visualization)

Install these dependencies using `pip` as mentioned in the usage section.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License

# My Open Source Project

This project is released under the Unlicense, which means it is in the public domain and free for anyone to use, modify, and distribute without any restrictions. You can find the full Unlicense text in the [UNLICENSE](UNLICENSE) file.

