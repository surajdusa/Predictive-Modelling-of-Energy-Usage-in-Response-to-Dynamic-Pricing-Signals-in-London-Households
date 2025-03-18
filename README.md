# Predictive Modelling of Energy Usage in Response to Dynamic Pricing Signals in London Households

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Source](#source)
- [Structure](#structure)
- [Prerequisites](#prerequisites)
- [Results](#results)
  - [LSTM Models](#lstm-models)
  - [GRU Models](#gru-models)
  - [ARIMA Models](#arima-models)
  - [VARIMA Models](#varima-models)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
This project aims to develop and compare time-series forecasting models to predict household energy consumption in response to dynamic pricing signals. The project utilizes historical energy usage data from London households and explores the impact of temporal, seasonal, and pricing variations on prediction accuracy.

## Dataset
The dataset used is a subset of the `CC_LCL-FullData.csv` file, containing energy consumption readings for London households.

## Source
London Datastore: [Smartmeter Energy Use Data in London Households](https://data.london.gov.uk/dataset/smartmeter-energy-use-data-in-london-households)

## Structure
The dataset includes the following columns:
- **Datetime**: Timestamp of the energy usage record
- **Energy Usage (KWH per half-hour)**: The amount of energy consumed in each 30-minute interval
- **Other relevant features** derived during preprocessing

## Prerequisites
Ensure you have the following installed:

- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Results
### LSTM Models
Achieved robust predictions with minimal deviation from actual data.

### GRU Models
Slightly improved training time with comparable prediction accuracy to LSTMs.

### ARIMA Models
Classical time-series forecasting approach with strong performance in capturing trends and seasonality.

### VARIMA Models
Multivariate forecasting approach that captures relationships between multiple energy usage variables.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.

## License
This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License - see the [LICENSE](LICENSE) file for details.

