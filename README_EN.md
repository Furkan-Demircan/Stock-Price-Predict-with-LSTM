# Stock Analysis and Forecasting

This project is a Jupyter Notebook designed for analyzing and forecasting historical closing prices of various stocks. It leverages Python's machine learning, data analysis, and visualization tools.

[**Read this document in Turkish**](./README.md)

## Features

- **Data Retrieval**: Downloads historical stock closing prices for specified date ranges using the `yfinance` library.
- **Data Visualization**: Provides graphical representations of price movements.
- **Machine Learning Models**: Implements models like LSTM for price forecasting. The model is trained on the closing prices of four different stocks.
- **Dropout and Early Stopping**: Applies Dropout layers and Early Stopping techniques to improve model accuracy and prevent overfitting.
- **Performance Metrics**: Evaluates models using various metrics (e.g., MAE, RMSE).

## Requirements

- Python 3.8 or above
- Required Python packages: `yfinance`, `pandas`, `numpy`, `tensorflow`, `matplotlib`, `sklearn`

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/Furkan-Demircan/stock-analysis.git
    cd stock-analysis
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Usage

1. After starting Jupyter Notebook, open the `Final.ipynb` file.
2. Select specific stocks and date ranges to run the analysis.
3. Train the models to forecast stock prices and evaluate the results. You can customize Dropout and Early Stopping settings to improve model accuracy.

## Contribution

Contributions are welcome! Please open an issue to discuss your changes before making them.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to your branch (`git push origin feature/new-feature`).
5. Open a pull request (PR).

## Contact

For questions or suggestions about this project, feel free to contact us:

- **Email**: goooglenudle@gmail.com
- **GitHub**: [Furkan-Demircan](https://github.com/Furkan-Demircan)

---

Happy analyzing!
