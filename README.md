# Stock Prediction using Machine Learning

This repository contains three Jupyter notebooks that demonstrate the use of machine learning techniques to predict stock prices.

## Notebooks

The repository includes three notebooks:

* [RandomForest.ipynb](RandomForest.ipynb): Demonstrates the use of Random Forest algorithm to predict stock prices.
* [SVM.ipynb](SVM.ipynb): Demonstrates the use of Support Vector Machine (SVM) algorithm to predict stock prices.
* [NeuralNet.ipynb](NeuralNet.ipynb): Demonstrates the use of a Neural Network to predict stock prices.

Each notebook follows the same structure and includes the following steps:

### Data Preprocessing

* Clean and preprocess the data by removing missing values and scaling the features.

### Feature Engineering

* Create new features such as rolling averages and trends to improve the model's performance.

### Model Training

* Train a machine learning model (Random Forest, SVM, or Neural Network) on the preprocessed data and evaluate its performance using metrics such as accuracy and confusion matrix.

## Additional Files

The repository also includes the following files:

* [Data.csv](Data.csv): The dataset used for training and testing the models.
* [RandomForest.py](RandomForest.py): The Python script used to train the Random Forest model.
* [SVM.py](SVM.py): The Python script used to train the SVM model.
* [neuralnet.py](neuralnet.py): A Python script that implements a neural network using the `Layer` class.
* [framework.py](framework.py): A Python script that implements the `Value` class, which is used for autograd graph construction.

## Requirements

The following libraries are required to run the notebooks:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter
* yfinance

## How to Run

To run the notebooks, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/stock-prediction.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Start Jupyter Notebook: `jupyter notebook`
4. Open the desired notebook (RandomForest.ipynb, SVM.ipynb, or NeuralNet.ipynb) and run the cells.

## License

This repository is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
