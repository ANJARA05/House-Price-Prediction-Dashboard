
# House Price Prediction Dashboard simple

A Machine Learning project developed using Python.

## Features
- House Price Prediction
- Tkinter GUI
- Machine Learning Model
- User-Friendly Dashboard

## Technologies Used
- Python
- Pandas
- Scikit-Learn
- Tkinter
- Matplotlib
- Joblib

- 
- # Technologies Used in details

### Python

Python was used as the main programming language to develop the entire House Price Prediction Dashboard application.

### Pandas

Pandas was used to load, read, and manage the housing dataset from the CSV file. It helped in handling and preparing data for machine learning.

### Scikit-Learn

Scikit-Learn was used to build and train the Linear Regression model. The model learns from historical house data and predicts house prices based on user inputs.

### Tkinter

Tkinter was used to create the graphical user interface (GUI), including input fields, buttons, labels, and the prediction dashboard.
buttns are:-

✅House Price Prediction Dashboard Window

✅ Area Input Field (Entry)

✅ Bedrooms Input Field (Entry)

✅ Bathrooms Input Field (Entry)

✅ Predict Price Button (Button)

✅ Prediction Result Display (Label)

✅ Attractive GUI Design (colors, fonts, layout)

### Matplotlib

 Data Visualization

  .. Matplotlib
   Matplotlib was used to visualize housing data through graphs and charts. It helped in analyzing the relationship between house features and house prices.

   ..Scatter Plot Analysis
  A scatter plot was created using Matplotlib to visualize the relationship between house area and house price. Each point on the graph represents a house, 
  
  where:

- X-axis represents the Area (square feet)
- Y-axis represents the House Price

The scatter plot helped in understanding the trend that larger houses generally have higher prices.

### Joblib

Joblib was used to save the trained machine learning model as a `.pkl` file and load it later in the application without retraining the model every time.
Joblib was used to save and load the trained machine learning model. After training the Linear Regression model, it was stored as a `model.pkl` file. This allowed the application to use the trained model directly without retraining it every time the program runs.

## Workflow

1. Load dataset using Pandas.
2. Visualize data using Matplotlib (Scatter Plot).
3. Train a Linear Regression model using Scikit-Learn.
4. Save the trained model using Joblib.
5. Load the saved model in the Tkinter application.
6. Accept user inputs and predict house prices.
7. Display the predicted result through the GUI.


## Author
Chhaya
