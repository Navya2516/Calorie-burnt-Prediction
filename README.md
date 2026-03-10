# Calorie Burnt Prediction using Machine Learning

## Project Overview

This project predicts the **number of calories burned during physical activity** using a Machine Learning model.

The application takes several physiological and activity-related parameters as input and estimates calorie expenditure using a trained ML pipeline.

The project also demonstrates how a **machine learning model can be integrated into a web application using FastAPI** for real-time predictions.

---

## Features

* Predict calories burned based on user inputs
* FastAPI-based backend for handling predictions
* Pre-trained ML pipeline for inference
* Clean separation of training and deployment
* Easy to run locally

---

## Machine Learning Model

The model predicts calories burned using the following features:

* Gender
* Age
* Height
* Weight
* Duration of Exercise
* Heart Rate
* Body Temperature

The trained model is stored as a **pickle file (`pipeline_model.pkl`)** which contains the full preprocessing and prediction pipeline.

---

## Project Structure

```
Calorie-burnt-Prediction/
│
├── Calories Burnt Prediction Using Machine Learning.ipynb
├── app.py
├── pipeline_model.pkl
├── requirements.txt
└── README.md
```

### File Description

**Calories Burnt Prediction Using Machine Learning.ipynb**
Contains data preprocessing, model training, and experimentation.

**app.py**
FastAPI application that loads the trained ML model and performs predictions.

**pipeline_model.pkl**
Serialized trained machine learning model.

**requirements.txt**
List of Python libraries required to run the project.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Navya2516/Calorie-burnt-Prediction.git
cd Calorie-burnt-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the FastAPI application:

```bash
python app.py
```

or

```bash
uvicorn app:app --reload
```

Then open your browser and go to:

```
http://localhost:8000
```

Enter the required inputs to get the **calorie burn prediction**.

---

## Technologies Used

* Python
* FastAPI
* Scikit-learn
* Pandas
* NumPy
* Uvicorn
* Jinja2 Templates

---

## Learning Outcomes

This project demonstrates:

* Building a machine learning regression model
* Saving models using **Pickle**
* Integrating ML models with **FastAPI**
* Creating an end-to-end ML prediction system

---

## Author

**Navya Saravanan**
Artificial Intelligence and Machine Learning Student

🔗 GitHub
https://github.com/Navya2516

🔗 LinkedIn
https://www.linkedin.com/in/navya-saravanan-8aa481311
