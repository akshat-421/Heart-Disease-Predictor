# Heart-Disease-Predictor
This is a machine learning classification project to predict the presence of heart disease based on patient medical data. The model has been deployed using Gradio and Hugging Face Spaces for easy web access.

This project was a part of the course [Complete A.I. & Machine Learning, Data Science Bootcamp by ZTM](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/?couponCode=CP130525) by [Andrei Neagoie](https://github.com/aneagoie) and [mrdbourke](https://github.com/mrdbourke).

I modified and extended the project by:
* Experimentation, ie, trying different models and different hyperparameters
* Building and deploying a user-friendly web app using Gradio
* Deploying the web app using Hugging Face to provide access to anyone

## Live Demo
[Try the heart disease predictor on Hugging Face Spaces](https://akshat421-heart-disease-predictor.hf.space/?__theme=system&deep_link=ZD0ckQ6dCl4)

## Project Overview
This model takes 13 clinical features as input and predicts whether a person is likely to have heart disease.

* Built with: Python, Scikit-learn, Gradio

* Dataset: UCI Heart Disease Dataset

* Deployment: Gradio + Hugging Face Spaces

* Model used: Logisitic Regression (primarily), Random Forest, CatBoost, XGBoost (experimentation)

## Features Used

| Feature        | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `age`          | Age of the person (in years)                                                |
| `sex`          | Sex (0 = female, 1 = male)                                                  |
| `cp`           | Chest pain type (0–3)                                                       |
| `trestbps`     | Resting blood pressure (in mm Hg)                                           |
| `chol`         | Serum cholesterol (in mg/dl)                                                |
| `fbs`          | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)                       |
| `restecg`      | Resting electrocardiographic results (0–2)                                  |
| `thalach`      | Maximum heart rate achieved                                                 |
| `exang`        | Exercise-induced angina (1 = yes, 0 = no)                                   |
| `oldpeak`      | ST depression induced by exercise relative to rest                          |
| `slope`        | Slope of the peak exercise ST segment (0–2)                                 |
| `ca`           | Number of major vessels (0–3) colored by fluoroscopy                        |
| `thal`         | Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)            |

## How to run locally
1. Clone this repo:
    ```bash
    git clone https://github.com/akshat-421/Heart-Disease-Predictor.git
    cd Heart-Disease-Predictor
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the app:
    ```bash
    python app.py
    ```
## Requirements
Contents of `requirements.txt`:
gradio
pandas
numpy
scikit-learn

## License
This project is open-source and available under the [MIT License](LICENSE).
