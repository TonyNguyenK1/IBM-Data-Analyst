
# Extracting and Visualizing Stock Data

## Overview

This project focuses on extracting and visualizing stock data using Python. It analyzes historical stock prices and revenue data to identify trends and insights.

## Features

- **Stock Data Analysis**:
  - Filters stock data up to a specified date.
  - Processes revenue data for analysis.
- **Custom Visualization**:
  - Generates dual-plot visualizations showing historical share prices and revenues.

## Data Analysis Process

1. **Data Filtering**:
   - Extracts relevant stock and revenue data up to specific dates.
   - Converts date columns into datetime format for accurate plotting.

2. **Graph Creation**:
   - Dual-plot visualization:
     - **Historical Share Price**: Displays the stock's closing price over time.
     - **Historical Revenue**: Shows revenue trends for the same period.

3. **Function Highlight**:
   - `make_graph_matplotlib`: Creates interactive or static visualizations based on libraries like Plotly or Matplotlib.

## Requirements

To run this project, you'll need the following Python libraries:
- `pandas`
- `plotly`

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/TonyNguyenK1/IBM-Data-Analyst/stock-data-visualization.git
   ```
2. Navigate to the directory:
   ```bash
   cd stock-data-visualization
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

The notebook provides clear visualizations of historical stock prices and revenues, enabling insights into financial trends.

## Future Work

- Add advanced financial analysis techniques.
- Integrate predictive modeling for stock price and revenue forecasting.
- Explore other datasets for extended analysis.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

## License

This project is licensed under the MIT License.
