# Iris Species Prediction

This repository contains a machine learning model for predicting iris flower species based on sepal and petal dimensions. It includes the dataset, model training, and a web application for predictions.

## Dataset
The dataset used is the famous **Iris dataset**, which consists of 150 samples from three species:
- **Setosa**
- **Versicolor**
- **Virginica**

Each sample has the following features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The `target` column represents the species, encoded as:
- `0`: Setosa
- `1`: Versicolor
- `2`: Virginica

## Project Structure
```
Iris-Species-Prediction/
│── app.py             # Flask web app for predictions
│── iris.csv           # Dataset
│── iris_model.pkl     # Trained ML model
│── irisdata.ipynb     # Jupyter Notebook with data analysis
│── features/          # Additional features (if any)
│── style.css          # Styling for the web app (in static folder under main project folder)
│── html1.html         # Frontend HTML file (in template folder under main project folder)
│── particles.json     # Visualization effects (in static folder under main project folder)
└── README.md          # Project documentation
```

## Model Training
The model was trained using a classification algorithm (e.g., Logistic Regression, Decision Tree, or Random Forest) on the Iris dataset. The trained model is stored as `iris_model.pkl`.

## How to Run
### 1. Install Dependencies
Ensure you have Python installed, then install the required packages:
```bash
pip install -r requirements.txt
```

### 2. Run the Web Application
Start the Flask app using:
```bash
python app.py
```
This will launch a local web server where you can input feature values and get predictions.

## Contributing
Feel free to fork this repository and make improvements. Pull requests are welcome!

## License
This project is open-source under the MIT License.

