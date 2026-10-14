# Logistic Regression Classification Project

This project uses **Logistic Regression** to make predictions with two datasets:

1. **Salary Classification** – predicts whether a salary is Low, Medium, or High using years of experience and education.
2. **Student Result Classification** – predicts whether a student will Pass or Fail using study hours, attendance percentage, and previous score.

The project uses Python, pandas, scikit-learn, Gradio, Flask, and joblib.

## Features

- Loads and explores two CSV datasets.
- Prepares numerical and categorical data.
- Splits data into training and testing sets.
- Trains two Logistic Regression models.
- Evaluates models using accuracy and classification reports.
- Provides prediction interfaces for salary level and student result.
- Displays class probabilities for predictions.
- Saves trained models as `.pkl` files.

## Requirements

- Python 3.9 or a compatible Python version
- The following Python libraries:
  - pandas
  - scikit-learn
  - gradio
  - flask
  - joblib

## Installation

Open Command Prompt or Anaconda Prompt in your project folder and run:

```bash
python -m pip install pandas scikit-learn gradio==4.44.1 flask joblib
```

If you are running the code in Jupyter Notebook, you can use:

```python
%pip install pandas scikit-learn gradio==4.44.1 flask joblib
```

After installing or changing packages in Jupyter Notebook, restart the kernel if imports fail.

## Dataset Files

Place these CSV files in the same working folder as your notebook or Python script:

- `salary_dataset.csv`
- `student_performance.csv`

### Salary dataset columns

| Column | Description |
|---|---|
| `Years_Experience` | Number of years of work experience |
| `Education` | Education level |
| `Salary` | Salary value included in the dataset |
| `Salary_Level` | Salary category: Low, Medium, or High |

The salary model uses `Years_Experience` and `Education` to predict `Salary_Level`.

### Student dataset columns

| Column | Description |
|---|---|
| `Study_Hours` | Hours spent studying |
| `Attendance_Pct` | Attendance percentage |
| `Previous_Score` | Previous score |
| `Exam_Marks` | Exam marks included in the dataset |
| `Result` | Student result: Pass or Fail |
| `Grade` | Student grade |

The student model uses `Study_Hours`, `Attendance_Pct`, and `Previous_Score` to predict `Result`.

## How to Run

### Option 1: Run in Jupyter Notebook

1. Open the project notebook in Jupyter Notebook.
2. Make sure both CSV files are in the notebook's working folder.
3. Run the cells in order, from installation and data loading to model training.
4. Run the interface cells to start the Gradio or Flask interface.
5. For the Flask interface, open this address in your browser while the application is running:

   `http://127.0.0.1:5000`

6. Select the Salary Model or Student Model page, enter the requested values, and click **Predict**.

If Flask is running in a notebook cell, keep that cell/kernel running while using the website.

### Option 2: Run as a Python Script

If you have saved the application code in a `.py` file, open a terminal in that folder and run:

```bash
python app.py
```

Use the filename of your actual Python script if it is not named `app.py`. The script must include the required data-loading and model-training code, or load already-trained models, before starting the interface.

## Model Training and Evaluation

The project uses an 80% training set and a 20% testing set with `random_state=42`. Numerical features are scaled with `StandardScaler`. The education feature in the salary model is encoded with `OneHotEncoder`.

Reported results from the provided run:

| Model | Test accuracy |
|---|---:|
| Salary Classification | 88.67% |
| Student Result Classification | 95.00% |

These are results from the dataset and run shown in the project output. Results may differ if the datasets or training settings change.

## Saved Models

The project saves the trained models using joblib:

- `salary_model.pkl`
- `student_model.pkl`

The files are created when the model-saving code runs. They can be loaded later with `joblib.load()` in a compatible Python environment.

## Troubleshooting

- **CSV file not found:** Check that both CSV files are in the notebook's current working folder, or provide the correct file paths.
- **Gradio import error:** Restart the notebook kernel after installing packages. Avoid repeatedly force-reinstalling packages in an active environment.
- **`HfFolder` import error:** This can indicate an incompatible `huggingface-hub` version. The provided environment used Gradio 4.44.1 with `huggingface-hub` 0.25.2, but package installation can fail if files are locked or permissions are insufficient. Restart Python and install compatible packages in a clean environment if necessary.
- **Flask page does not open:** Make sure the Flask cell is running and use `http://127.0.0.1:5000` on the same computer.
- **Port 5000 is busy:** Stop the other application using that port or configure Flask to use another available port.

## Technologies Used

- Python
- pandas
- scikit-learn
- Logistic Regression
- Gradio
- Flask
- joblib

## Project Purpose

This is an educational machine learning project for practicing classification, preprocessing, model evaluation, and simple prediction interfaces.
