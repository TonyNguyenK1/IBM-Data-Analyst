
# Exploratory Data Analysis: Car Price Prediction

## Overview

This project performs exploratory data analysis (EDA) on a dataset of cars to understand the relationships between various features and car prices. The aim is to identify key characteristics that most influence car prices, laying the foundation for predictive modeling.

## Features

- **Correlation Analysis**: Explores the linear relationship between car price and attributes such as horsepower, engine size, and fuel efficiency.
- **Significant Insights**: Identifies key variables most relevant to predicting car prices.
- **Data Visualization**: Provides basic visualizations to support findings (future addition).

## Data Analysis Process

1. **Correlation vs. Causation**:
   - Differentiating between correlation and causation.
   - Understanding Pearson Correlation and P-values.

2. **Key Attributes Analyzed**:
   - Continuous Variables:
     - `length`, `width`, `curb-weight`, `engine-size`, `horsepower`, `city-mpg`, `highway-mpg`, `wheel-base`, `bore`
   - Categorical Variables:
     - `drive-wheels`

3. **Findings**:
   - Strong Positive Correlations:
     - `engine-size (0.87)`, `curb-weight (0.83)`, `horsepower (0.81)`, `width (0.75)`
   - Strong Negative Correlations:
     - `city-mpg (-0.69)`, `highway-mpg (-0.70)`
   - Moderate Correlations:
     - `wheel-base (0.58)`, `length (0.69)`, `bore (0.54)`

4. **Key Outcomes**:
   - Identifies variables critical for car price predictions.

## Requirements

To run this project, you'll need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/TonyNguyenK1/IBM-Data-Analys/eda-car-price.git
   ```
2. Navigate to the directory:
   ```bash
   cd eda-car-price
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   ```bash
   jupyter notebook
   ```

## Results

The analysis identifies key features significantly correlated with car price. These insights can be used to build predictive models in future projects.

## Future Work

- Add advanced visualizations.
- Implement predictive modeling (e.g., regression or machine learning models).
- Explore additional datasets for further analysis.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

## License

This project is licensed under the MIT License.
