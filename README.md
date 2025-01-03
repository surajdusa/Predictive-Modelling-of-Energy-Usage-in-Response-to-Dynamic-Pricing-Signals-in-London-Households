Predictive Modelling of Energy Usage in Response to Dynamic Pricing Signals in London Households


Overview - This project aims to develop and compare time-series forecasting models to predict household energy consumption in response to dynamic pricing signals. The project utilizes historical energy usage data from London households and explores the impact of temporal, seasonal, and pricing variations on prediction accuracy.

Dataset: The dataset used is a subset of the CC_LCL-FullData.csv file, containing energy consumption readings for London households.

Source: London Datastore (https://data.london.gov.uk/dataset/smartmeter-energy-use-data-in-london-households)

Structure: Includes columns for datetime, energy usage (KWH per half-hour), and other relevant features derived during preprocessing.


Prerequisites

Ensure you have the following installed:
- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Pandas
- Matplotlib
- Seaborn


Results
- LSTM Models: Achieved robust predictions with minimal deviation from actual data.
- GRU Models: Slightly improved training time with comparable prediction accuracy to LSTMs.


Contributing: Contributions are welcome! Please fork the repository and submit a pull request for review.
