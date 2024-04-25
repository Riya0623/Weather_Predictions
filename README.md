# Weather_Predictions

## Weather Predictions

This repository contains Python code for weather predictions based on historical weather data. The primary dataset used is `weather.csv`, which is loaded using pandas and analyzed to forecast various weather parameters. The main functionalities of the code are outlined below:

### Key Features:
- **Data Loading and Preprocessing**: The code loads the weather dataset (`weather.csv`) and preprocesses it by selecting columns with less than 5% missing values for further analysis.

- **Visualization**: The script includes visualization capabilities to plot snow depth (`snwd`) over time, providing a graphical representation of this weather attribute.

- **Backtesting Function**: A backtesting function (`backtest`) is implemented to evaluate the performance of weather prediction models. This function splits the dataset into training and testing sets, fits the model, and computes predictions using a specified step interval. Model performance is assessed using mean absolute error.

- **Rolling Window Computation**: The code calculates rolling averages for specific weather attributes (`tmax`, `tmin`, `prcp`) over different horizons. This helps in understanding trends and variations in weather patterns.

- **Prediction Evaluation**: The script visualizes the accuracy of predictions by plotting a histogram of the differences between actual and predicted values, offering insights into model performance across different time periods.

### Usage:
To use this codebase, follow these steps:
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your_username/weather-predictions.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python weather_predictions.py
   ```

### Dependencies:
- `numpy`
- `pandas`
- `scikit-learn`

### Contribution:
Contributions to this project are welcome. If you have suggestions for improvements or would like to add new features, please fork the repository and submit a pull request with your changes.


