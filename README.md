# Used Car Price Prediction 🚗

A machine learning project that predicts the selling price of used cars based on vehicle-related features.

## 📌 Project Overview

This project uses machine learning to estimate used car selling prices using features such as:

* Car brand/model
* Manufacturing year
* Fuel type
* Transmission
* Engine
* Maximum power
* Torque
* Number of seats
* Mileage
* Kilometers driven
* Owner type
* Seller type

The target variable is `Selling_Price`.

## 🎯 Objective

To develop a machine learning model that can predict the selling price of a used car from historical vehicle data.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## 🔄 Methodology

1. Load the used-car dataset.
2. Inspect the dataset and its structure.
3. Check and remove missing values.
4. Perform exploratory data analysis.
5. Separate features and target variable.
6. Convert categorical variables using one-hot encoding.
7. Split the data into training and testing sets using an 80:20 ratio.
8. Train a Linear Regression model.
9. Generate predictions.
10. Evaluate the model using MAE, MSE and R² score.

## 🤖 Machine Learning Model

**Linear Regression**

The model was trained using 80% of the dataset and evaluated using the remaining 20%.

## 📊 Results

The model achieved the following results on the test dataset:

| Metric   |         Result |
| -------- | -------------: |
| R² Score |         0.9668 |
| MAE      |        ₹74,657 |
| MSE      | 23,072,907,057 |

The R² score indicates that the model explains a large portion of the variation in the test data.

## 📈 Visualizations

The notebook includes visualizations for:

* Selling price distribution
* Car age vs selling price
* Cars by fuel type
* Cars by transmission type
* Actual vs predicted selling prices

## 🚘 Prediction

The notebook also contains an interactive section where users can enter vehicle details and obtain a predicted selling price.

## ⚠️ Limitations

The prediction depends on the quality and characteristics of the dataset. Real-world prices can also depend on factors such as:

* Vehicle condition
* Location
* Service history
* Accident history
* Market demand

These factors may not be fully represented in the dataset.

## 📁 Project Structure

```text
used-car-price-prediction/
│
├── Used_Car_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

## 🚀 How to Run

### Option 1 — Google Colab

Open the notebook in Google Colab and run the cells sequentially.

### Option 2 — Local Jupyter Notebook

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open:

```bash
jupyter notebook
```

and run `Used_Car_Price_Prediction.ipynb`.

## 👨‍💻 Author

Machine Learning project developed as part of a portfolio project.
