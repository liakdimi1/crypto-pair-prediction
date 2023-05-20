# Crypto Pairs Prediction

This project focuses on predicting the price movement of crypto pairs using deep learning techniques. It utilizes recurrent neural networks (RNN) to capture temporal dependencies in the data and make predictions based on historical price patterns.

#Dataset

The dataset used in this project is sourced from the "392 Crypto Currency Pairs at Minute Resolution" dataset. It provides minute-level price data for various crypto pairs. The dataset is preprocessed and resampled to a 1-minute interval to facilitate training and prediction.

# Project Structure

The project directory contains the following files:

crypto_pairs_prediction.ipynb: Jupyter Notebook file containing the code and analysis for the project.
solusd.csv: CSV file containing the raw price data for the SOL/USD crypto pair.
README.md: This file, providing an overview and instructions for the project.

# Setup and Dependencies
To run the project, you need to have the following dependencies installed:

Python 3.x
TensorFlow (version X.X.X)
Keras (version X.X.X)
Pandas (version X.X.X)
NumPy (version X.X.X)
Matplotlib (version X.X.X)
It is recommended to set up a virtual environment and install the dependencies using the requirements.txt file.

# Usage

Start by downloading or cloning the project repository.
Install the required dependencies using the provided requirements.txt file.
Place your own dataset file or use the provided solusd.csv file.
Open the crypto_pairs_prediction.ipynb notebook.
Run the notebook cells sequentially to preprocess the data, build the RNN model, train the model, and make predictions.
Explore the results, including evaluation metrics and visualizations.
Modify the code and experiment with different model architectures or hyperparameters to improve performance.
Use the trained model to make predictions on new, unseen data.

# Results
The project evaluates the model's performance using various evaluation metrics, including mean squared error (MSE), mean absolute error (MAE), and R-squared (R^2) score. The results are displayed and discussed in the notebook, along with visualizations of the predicted price movements compared to the actual values.

#Contributing

Contributions to the project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

# License
This project is licensed under the MIT License.

# Acknowledgements
We would like to acknowledge the authors of the "392 Crypto Currency Pairs at Minute Resolution" dataset for providing the valuable data for this project.

Please feel free to customize this README file based on your specific project details, instructions, and requirements.
