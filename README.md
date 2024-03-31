# NBA Points Per Game Linear Regression (Gradient Descent)

This project implements a simple linear regression model to predict the points per game (PTS) of NBA players based on various features such as minutes played (MP), field goals made (FG), field goals attempted (FGA), field goal percentage (FG%), three-point percentage (3P%), two-point percentage (2P%), and free throw percentage (FT%).

## Usage
To train a model which can predict/estimate the PTS of NBA players using Multiple linear regression (Gradient Descent)

## Requirements
- [Python 3](https://www.python.org/) <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
- [NumPy](https://numpy.org/) <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" alt="NumPy" width="40" height="40"/> 
- [pandas](https://pandas.pydata.org/) <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> 
- [matplotlib](https://matplotlib.org/) <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" width="40" height="40"/> 

## Installation
To get started with the NBA Points Per Game Linear Regression project, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Urawit/NBA-PTS-Regression.git
    cd NBA-PTS-Regression
    ```
    This will clone the repository to your local machine and navigate into the project directory.

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
    This command will install all the required dependencies specified in the `requirements.txt` file. Make sure you have Python installed and pip available in your environment before executing this command.

## Code Explanation
The `linear_regression.py` script contains the implementation of the `linear_regression_MultipleD` class, which performs the following steps:
1. Initializes the linear regression model with parameters.
2. Fits the model to the provided dataset using gradient descent.
3. Computes the loss function (mean squared error) and updates the model parameters iteratively.
4. Visualizes the loss function versus the number of iterations.
5. Plots the predicted versus actual points per game.
6. Calculates the Root Mean Square Error (RMSE) to evaluate the model's performance.

## Dataset
The dataset used in this project contains NBA player statistics for the 2022-2023 regular season. It includes features such as minutes played, field goals made, field goals attempted, field goal percentage, three-point percentage, two-point percentage, free throw percentage, and points per game.

## Results
The linear regression model successfully predicts the points per game of NBA players based on the provided features. The RMSE value provides insight into the model's accuracy, and visualizations help understand the relationship between predicted and actual points per game.

## License
This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
