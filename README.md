# Student Performance Prediction

## Overview

This project is a Machine Learning web application that predicts a student's academic performance based on various factors such as gender, parental education level, lunch type, test preparation course, reading score, and writing score.

The application is built using Python, Flask, Scikit-learn, and HTML/CSS. Users can enter student details through a web interface and receive a predicted mathematics score.

---

## Features

* User-friendly web interface
* Machine Learning-based prediction system
* Data preprocessing pipeline
* Model training and evaluation
* Real-time predictions through Flask
* Responsive design

---

## Tech Stack

### Backend

* Python
* Flask

### Machine Learning

* Scikit-learn
* Pandas
* NumPy

### Frontend

* HTML
* CSS

### Deployment

* Render

---

## Dataset

The project uses the Student Performance Dataset containing the following features:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

### Target Variable

* Mathematics Score

---

## Project Structure

student-performance-prediction/

├── artifacts/

├── notebooks/

├── src/

│ ├── components/

│ ├── pipeline/

│ ├── exception.py

│ ├── logger.py

│ └── utils.py

├── templates/

├── static/

├── app.py

├── requirements.txt

└── README.md

---

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd student-performance-prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## Machine Learning Pipeline

1. Data Ingestion
2. Data Validation
3. Data Transformation
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction Pipeline
8. Deployment

---

## Results

The model is trained to predict students' mathematics scores based on demographic and academic attributes.

Performance is evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---


## Author

Yash Singh

B.Tech (AI & ML)

Machine Learning & Software Development Enthusiast

---

## License

This project is licensed under the MIT License.
