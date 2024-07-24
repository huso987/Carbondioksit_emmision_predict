# CO2 Emissions Prediction

This project focuses on predicting CO2 emissions from vehicles using a Simple Linear Regression model. The dataset used for this analysis contains information about various vehicles, including their engine size, fuel consumption, and CO2 emissions.

## Dataset

The dataset includes the following features:
- `Make`: The manufacturer of the vehicle.
- `Model`: The model of the vehicle.
- `Vehicle Class`: The class of the vehicle (e.g., SUV, Sedan).
- `Engine Size(L)`: The size of the vehicle's engine in liters.
- `Cylinders`: The number of cylinders in the vehicle's engine.
- `Transmission`: The type of transmission (e.g., Automatic, Manual).
- `Fuel Type`: The type of fuel used by the vehicle (e.g., Gasoline, Diesel).
- `Fuel Consumption City (L/100 km)`: Fuel consumption in the city.
- `Fuel Consumption Hwy (L/100 km)`: Fuel consumption on the highway.
- `Fuel Consumption Comb (L/100 km)`: Combined fuel consumption.
- `Fuel Consumption Comb (mpg)`: Combined fuel consumption in miles per gallon.
- `CO2 Emissions(g/km)`: CO2 emissions in grams per kilometer.

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `plotly`, `scipy`, `sklearn`, `yellowbrick`

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/huso987/CO2-Emissions-Prediction.git
    cd CO2-Emissions-Prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Analysis and Modeling

### Data Exploration and Visualization

![image](https://github.com/user-attachments/assets/f43a0eb1-1332-4067-b544-d5086838c2b9)

![image](https://github.com/user-attachments/assets/d50346d8-e1ea-444e-9832-c9da97b841fc)

![image](https://github.com/user-attachments/assets/62b0528f-26d9-4bd8-94b0-370d57020bd3)


### Model Building

- A Simple Linear Regression model is built to predict `co2` emissions using `engine_size`.
- Train-test split is used to evaluate the model.
- Model evaluation includes metrics such as R-squared, MAE, MSE, RMSE, and residual plots.

### Outlier Analysis and Skewness

![image](https://github.com/user-attachments/assets/e8d5fab9-0ef8-4efd-8fa7-940944c821a6)                        ![image](https://github.com/user-attachments/assets/a7d8ba05-4169-469c-894d-17137d5bf55e)


## Results

![image](https://github.com/user-attachments/assets/c6fc7cca-9769-44e5-abf2-47d03b032c33)


## Future Work

- Explore more complex models such as Polynomial Regression, Ridge, Lasso, and ElasticNet.
- Feature engineering to create new features from existing data.
- Hyperparameter tuning using GridSearchCV.


---

Feel free to reach out for any queries or suggestions!

Hüseyin
