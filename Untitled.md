```python
%pip install pandas scikit-learn gradio flask joblib
```

    Defaulting to user installation because normal site-packages is not writeable
    Requirement already satisfied: pandas in c:\programdata\anaconda3\lib\site-packages (1.4.2)
    Requirement already satisfied: scikit-learn in c:\programdata\anaconda3\lib\site-packages (1.0.2)
    Requirement already satisfied: gradio in c:\users\24108224\appdata\roaming\python\python39\site-packages (4.44.1)
    Note: you may need to restart the kernel to use updated packages.
    Requirement already satisfied: flask in c:\programdata\anaconda3\lib\site-packages (1.1.2)
    Requirement already satisfied: joblib in c:\programdata\anaconda3\lib\site-packages (1.1.0)
    Requirement already satisfied: numpy>=1.18.5 in c:\programdata\anaconda3\lib\site-packages (from pandas) (1.21.5)
    Requirement already satisfied: pytz>=2020.1 in c:\programdata\anaconda3\lib\site-packages (from pandas) (2021.3)
    Requirement already satisfied: python-dateutil>=2.8.1 in c:\programdata\anaconda3\lib\site-packages (from pandas) (2.8.2)
    Requirement already satisfied: threadpoolctl>=2.0.0 in c:\programdata\anaconda3\lib\site-packages (from scikit-learn) (2.2.0)
    Requirement already satisfied: scipy>=1.1.0 in c:\programdata\anaconda3\lib\site-packages (from scikit-learn) (1.7.3)
    Requirement already satisfied: huggingface-hub>=0.19.3 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.25.2)
    Requirement already satisfied: typing-extensions~=4.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (4.16.0)
    Requirement already satisfied: packaging in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (26.3)
    Requirement already satisfied: tomlkit==0.12.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.12.0)
    Requirement already satisfied: pydub in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.25.1)
    Requirement already satisfied: anyio<5.0,>=3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (4.12.1)
    Requirement already satisfied: semantic-version~=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (2.10.0)
    Requirement already satisfied: pydantic>=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (2.13.5)
    Requirement already satisfied: orjson~=3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (3.11.5)
    Requirement already satisfied: pillow<11.0,>=8.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (9.0.1)
    Requirement already satisfied: gradio-client==1.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (1.3.0)
    Requirement already satisfied: typer<1.0,>=0.12 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.23.2)
    Requirement already satisfied: jinja2<4.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (2.11.3)
    Requirement already satisfied: ruff>=0.2.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.17.0)
    Requirement already satisfied: markupsafe~=2.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (2.0.1)
    Requirement already satisfied: matplotlib~=3.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (3.5.1)
    Requirement already satisfied: pyyaml<7.0,>=5.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (6.0.3)
    Requirement already satisfied: uvicorn>=0.14.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.39.0)
    Requirement already satisfied: httpx>=0.24.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.28.1)
    Requirement already satisfied: ffmpy in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (1.0.0)
    Requirement already satisfied: fastapi<1.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.128.8)
    Requirement already satisfied: importlib-resources<7.0,>=1.3 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (6.5.2)
    Requirement already satisfied: python-multipart>=0.0.9 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.0.20)
    Requirement already satisfied: aiofiles<24.0,>=22.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (23.2.1)
    Requirement already satisfied: urllib3~=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (2.6.3)
    Requirement already satisfied: fsspec in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio-client==1.3.0->gradio) (2025.10.0)
    Requirement already satisfied: websockets<13.0,>=10.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio-client==1.3.0->gradio) (12.0)
    Requirement already satisfied: click>=5.1 in c:\programdata\anaconda3\lib\site-packages (from flask) (8.0.4)
    Requirement already satisfied: itsdangerous>=0.24 in c:\programdata\anaconda3\lib\site-packages (from flask) (2.0.1)
    Requirement already satisfied: Werkzeug>=0.15 in c:\programdata\anaconda3\lib\site-packages (from flask) (2.0.3)
    Requirement already satisfied: exceptiongroup>=1.0.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from anyio<5.0,>=3.0->gradio) (1.3.1)
    Requirement already satisfied: idna>=2.8 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from anyio<5.0,>=3.0->gradio) (3.20)
    Requirement already satisfied: colorama in c:\users\24108224\appdata\roaming\python\python39\site-packages (from click>=5.1->flask) (0.4.6)
    Requirement already satisfied: annotated-doc>=0.0.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio) (0.0.5)
    Requirement already satisfied: typing-inspection>=0.4.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio) (0.4.2)
    Requirement already satisfied: starlette<1.0.0,>=0.40.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio) (0.49.3)
    Requirement already satisfied: certifi in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpx>=0.24.1->gradio) (2026.7.22)
    Requirement already satisfied: httpcore==1.* in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpx>=0.24.1->gradio) (1.0.9)
    Requirement already satisfied: h11>=0.16 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpcore==1.*->httpx>=0.24.1->gradio) (0.16.0)
    Requirement already satisfied: requests in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio) (2.32.5)
    Requirement already satisfied: tqdm>=4.42.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio) (4.70.1)
    Requirement already satisfied: filelock in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio) (3.19.1)
    Requirement already satisfied: zipp>=3.1.0 in c:\programdata\anaconda3\lib\site-packages (from importlib-resources<7.0,>=1.3->gradio) (3.7.0)
    Requirement already satisfied: kiwisolver>=1.0.1 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (1.3.2)
    Requirement already satisfied: fonttools>=4.22.0 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (4.25.0)
    Requirement already satisfied: pyparsing>=2.2.1 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (3.0.4)
    Requirement already satisfied: cycler>=0.10 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (0.11.0)
    Requirement already satisfied: annotated-types>=0.6.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from pydantic>=2.0->gradio) (0.7.0)
    Requirement already satisfied: pydantic-core==2.46.5 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from pydantic>=2.0->gradio) (2.46.5)
    Requirement already satisfied: six>=1.5 in c:\programdata\anaconda3\lib\site-packages (from python-dateutil>=2.8.1->pandas) (1.16.0)
    Requirement already satisfied: shellingham>=1.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from typer<1.0,>=0.12->gradio) (1.5.4)
    Requirement already satisfied: rich>=12.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from typer<1.0,>=0.12->gradio) (15.0.0)
    Requirement already satisfied: pygments<3.0.0,>=2.13.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from rich>=12.3.0->typer<1.0,>=0.12->gradio) (2.21.0)
    Requirement already satisfied: markdown-it-py>=2.2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from rich>=12.3.0->typer<1.0,>=0.12->gradio) (3.0.0)
    Requirement already satisfied: mdurl~=0.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from markdown-it-py>=2.2.0->rich>=12.3.0->typer<1.0,>=0.12->gradio) (0.1.2)
    Requirement already satisfied: charset_normalizer<4,>=2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from requests->huggingface-hub>=0.19.3->gradio) (3.5.2)
    


```python
import pandas as pd

salary_df = pd.read_csv("salary_dataset.csv")
student_df = pd.read_csv("student_performance.csv")

print("SALARY DATASET")
print(salary_df.head())
print(salary_df.info())

print("\nSTUDENT PERFORMANCE DATASET")
print(student_df.head())
print(student_df.info())
```

    SALARY DATASET
       Years_Experience Education  Salary Salary_Level
    0               4.4  Bachelor   39408          Low
    1               1.2       PhD   46233          Low
    2               7.4    Master   66722       Medium
    3               9.0  Bachelor   62322          Low
    4               4.2    Master   47081          Low
    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 1500 entries, 0 to 1499
    Data columns (total 4 columns):
     #   Column            Non-Null Count  Dtype  
    ---  ------            --------------  -----  
     0   Years_Experience  1500 non-null   float64
     1   Education         1500 non-null   object 
     2   Salary            1500 non-null   int64  
     3   Salary_Level      1500 non-null   object 
    dtypes: float64(1), int64(1), object(2)
    memory usage: 47.0+ KB
    None
    
    STUDENT PERFORMANCE DATASET
       Study_Hours  Attendance_Pct  Previous_Score  Exam_Marks Result Grade
    0          6.4            83.1            67.7        78.8   Pass     A
    1          9.0            57.0            74.4        89.5   Pass    A+
    2          7.9            65.0            67.0        82.8   Pass     A
    3          2.6            95.9            41.3        46.0   Fail     C
    4          3.4            68.7            42.4        45.4   Fail     C
    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 1500 entries, 0 to 1499
    Data columns (total 6 columns):
     #   Column          Non-Null Count  Dtype  
    ---  ------          --------------  -----  
     0   Study_Hours     1500 non-null   float64
     1   Attendance_Pct  1500 non-null   float64
     2   Previous_Score  1500 non-null   float64
     3   Exam_Marks      1500 non-null   float64
     4   Result          1500 non-null   object 
     5   Grade           1500 non-null   object 
    dtypes: float64(4), object(2)
    memory usage: 70.4+ KB
    None
    


```python
from sklearn.model_selection import train_test_split
from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import OneHotEncoder, StandardScaler
from sklearn.pipeline import Pipeline
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, classification_report

# -------------------------------
# MODEL 1: SALARY CLASSIFICATION
# -------------------------------

X_salary = salary_df[
    ["Years_Experience", "Education"]
]

y_salary = salary_df["Salary_Level"]

X_train_salary, X_test_salary, y_train_salary, y_test_salary = (
    train_test_split(
        X_salary,
        y_salary,
        test_size=0.2,
        random_state=42,
        stratify=y_salary
    )
)

salary_preprocessor = ColumnTransformer([
    ("numeric", StandardScaler(), ["Years_Experience"]),
    ("categorical", OneHotEncoder(handle_unknown="ignore"), ["Education"])
])

salary_model = Pipeline([
    ("preprocessor", salary_preprocessor),
    ("classifier", LogisticRegression(max_iter=1000))
])

salary_model.fit(X_train_salary, y_train_salary)

salary_predictions = salary_model.predict(X_test_salary)

print("SALARY MODEL ACCURACY:")
print(accuracy_score(y_test_salary, salary_predictions))

print("\nSALARY CLASSIFICATION REPORT:")
print(classification_report(y_test_salary, salary_predictions))


# ----------------------------------
# MODEL 2: STUDENT RESULT CLASSIFICATION
# ----------------------------------

X_student = student_df[
    ["Study_Hours", "Attendance_Pct", "Previous_Score"]
]

y_student = student_df["Result"]

X_train_student, X_test_student, y_train_student, y_test_student = (
    train_test_split(
        X_student,
        y_student,
        test_size=0.2,
        random_state=42,
        stratify=y_student
    )
)

student_preprocessor = ColumnTransformer([
    ("numeric", StandardScaler(),
     ["Study_Hours", "Attendance_Pct", "Previous_Score"])
])

student_model = Pipeline([
    ("preprocessor", student_preprocessor),
    ("classifier", LogisticRegression(max_iter=1000))
])

student_model.fit(X_train_student, y_train_student)

student_predictions = student_model.predict(X_test_student)

print("\nSTUDENT MODEL ACCURACY:")
print(accuracy_score(y_test_student, student_predictions))

print("\nSTUDENT CLASSIFICATION REPORT:")
print(classification_report(y_test_student, student_predictions))
```

    SALARY MODEL ACCURACY:
    0.8866666666666667
    
    SALARY CLASSIFICATION REPORT:
                  precision    recall  f1-score   support
    
            High       0.94      0.93      0.93       100
             Low       0.92      0.87      0.89       100
          Medium       0.81      0.86      0.83       100
    
        accuracy                           0.89       300
       macro avg       0.89      0.89      0.89       300
    weighted avg       0.89      0.89      0.89       300
    
    
    STUDENT MODEL ACCURACY:
    0.95
    
    STUDENT CLASSIFICATION REPORT:
                  precision    recall  f1-score   support
    
            Fail       0.88      0.92      0.90        71
            Pass       0.97      0.96      0.97       229
    
        accuracy                           0.95       300
       macro avg       0.93      0.94      0.93       300
    weighted avg       0.95      0.95      0.95       300
    
    


```python
%pip install gradio
```

    Defaulting to user installation because normal site-packages is not writeable
    Requirement already satisfied: gradio in c:\users\24108224\appdata\roaming\python\python39\site-packages (4.44.1)
    Requirement already satisfied: pillow<11.0,>=8.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (9.0.1)
    Requirement already satisfied: jinja2<4.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (2.11.3)
    Requirement already satisfied: orjson~=3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (3.11.5)
    Requirement already satisfied: ruff>=0.2.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.17.0)
    Requirement already satisfied: matplotlib~=3.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (3.5.1)
    Requirement already satisfied: anyio<5.0,>=3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (4.12.1)
    Requirement already satisfied: aiofiles<24.0,>=22.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (23.2.1)
    Requirement already satisfied: numpy<3.0,>=1.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (1.21.5)
    Requirement already satisfied: python-multipart>=0.0.9 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.0.20)
    Requirement already satisfied: typing-extensions~=4.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (4.16.0)
    Requirement already satisfied: pyyaml<7.0,>=5.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (6.0)
    Requirement already satisfied: pydub in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.25.1)
    Requirement already satisfied: huggingface-hub>=0.19.3 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (1.8.0)
    Requirement already satisfied: pandas<3.0,>=1.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (1.4.2)
    Requirement already satisfied: packaging in c:\programdata\anaconda3\lib\site-packages (from gradio) (21.3)
    Requirement already satisfied: ffmpy in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (1.0.0)
    Requirement already satisfied: urllib3~=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (2.6.3)
    Requirement already satisfied: pydantic>=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (2.13.5)
    Requirement already satisfied: importlib-resources<7.0,>=1.3 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (6.5.2)
    Requirement already satisfied: gradio-client==1.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (1.3.0)
    Requirement already satisfied: tomlkit==0.12.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.12.0)
    Requirement already satisfied: uvicorn>=0.14.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.39.0)
    Requirement already satisfied: httpx>=0.24.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.28.1)
    Requirement already satisfied: markupsafe~=2.0 in c:\programdata\anaconda3\lib\site-packages (from gradio) (2.0.1)
    Requirement already satisfied: semantic-version~=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (2.10.0)
    Requirement already satisfied: typer<1.0,>=0.12 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.23.2)
    Requirement already satisfied: fastapi<1.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio) (0.128.8)
    Requirement already satisfied: websockets<13.0,>=10.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio-client==1.3.0->gradio) (12.0)
    Requirement already satisfied: fsspec in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio-client==1.3.0->gradio) (2025.10.0)
    Requirement already satisfied: exceptiongroup>=1.0.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from anyio<5.0,>=3.0->gradio) (1.3.1)
    Requirement already satisfied: idna>=2.8 in c:\programdata\anaconda3\lib\site-packages (from anyio<5.0,>=3.0->gradio) (3.3)
    Requirement already satisfied: starlette<1.0.0,>=0.40.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio) (0.49.3)
    Requirement already satisfied: typing-inspection>=0.4.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio) (0.4.2)
    Requirement already satisfied: annotated-doc>=0.0.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio) (0.0.5)
    Requirement already satisfied: httpcore==1.* in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpx>=0.24.1->gradio) (1.0.9)
    Requirement already satisfied: certifi in c:\programdata\anaconda3\lib\site-packages (from httpx>=0.24.1->gradio) (2021.10.8)
    Requirement already satisfied: h11>=0.16 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpcore==1.*->httpx>=0.24.1->gradio) (0.16.0)
    Requirement already satisfied: tqdm>=4.42.1 in c:\programdata\anaconda3\lib\site-packages (from huggingface-hub>=0.19.3->gradio) (4.64.0)
    Requirement already satisfied: filelock>=3.10.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio) (3.19.1)
    Requirement already satisfied: hf-xet<2.0.0,>=1.4.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio) (1.7.0)
    Requirement already satisfied: zipp>=3.1.0 in c:\programdata\anaconda3\lib\site-packages (from importlib-resources<7.0,>=1.3->gradio) (3.7.0)
    Requirement already satisfied: python-dateutil>=2.7 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (2.8.2)
    Requirement already satisfied: cycler>=0.10 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (0.11.0)
    Requirement already satisfied: fonttools>=4.22.0 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (4.25.0)
    Requirement already satisfied: kiwisolver>=1.0.1 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (1.3.2)
    Requirement already satisfied: pyparsing>=2.2.1 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio) (3.0.4)
    Requirement already satisfied: pytz>=2020.1 in c:\programdata\anaconda3\lib\site-packages (from pandas<3.0,>=1.0->gradio) (2021.3)
    Requirement already satisfied: annotated-types>=0.6.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from pydantic>=2.0->gradio) (0.7.0)
    Requirement already satisfied: pydantic-core==2.46.5 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from pydantic>=2.0->gradio) (2.46.5)
    Requirement already satisfied: six>=1.5 in c:\programdata\anaconda3\lib\site-packages (from python-dateutil>=2.7->matplotlib~=3.0->gradio) (1.16.0)
    Requirement already satisfied: colorama in c:\programdata\anaconda3\lib\site-packages (from tqdm>=4.42.1->huggingface-hub>=0.19.3->gradio) (0.4.4)
    Requirement already satisfied: click>=8.0.0 in c:\programdata\anaconda3\lib\site-packages (from typer<1.0,>=0.12->gradio) (8.0.4)
    Requirement already satisfied: shellingham>=1.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from typer<1.0,>=0.12->gradio) (1.5.4)
    Requirement already satisfied: rich>=12.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from typer<1.0,>=0.12->gradio) (15.0.0)
    Requirement already satisfied: pygments<3.0.0,>=2.13.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from rich>=12.3.0->typer<1.0,>=0.12->gradio) (2.21.0)
    Requirement already satisfied: markdown-it-py>=2.2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from rich>=12.3.0->typer<1.0,>=0.12->gradio) (3.0.0)
    Requirement already satisfied: mdurl~=0.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from markdown-it-py>=2.2.0->rich>=12.3.0->typer<1.0,>=0.12->gradio) (0.1.2)
    Note: you may need to restart the kernel to use updated packages.
    


```python
import gradio as gr

print("Gradio installed successfully!")
print("Version:", gr.__version__)
```

    Gradio installed successfully!
    Version: 4.44.1
    


```python
import sys

print(sys.version)
print(sys.executable)
```

    3.9.12 (main, Apr  4 2022, 05:22:27) [MSC v.1916 64 bit (AMD64)]
    C:\ProgramData\Anaconda3\python.exe
    


```python
%pip uninstall -y gradio gradio-client
%pip install gradio==4.44.1
```

    Found existing installation: gradio 4.44.1
    Uninstalling gradio-4.44.1:
      Successfully uninstalled gradio-4.44.1
    Found existing installation: gradio-client 1.3.0
    Uninstalling gradio-client-1.3.0:
      Successfully uninstalled gradio-client-1.3.0
    Note: you may need to restart the kernel to use updated packages.
    Defaulting to user installation because normal site-packages is not writeable
    Collecting gradio==4.44.1
      Using cached gradio-4.44.1-py3-none-any.whl (18.1 MB)
    Requirement already satisfied: importlib-resources<7.0,>=1.3 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (6.5.2)
    Requirement already satisfied: markupsafe~=2.0 in c:\programdata\anaconda3\lib\site-packages (from gradio==4.44.1) (2.0.1)
    Requirement already satisfied: ffmpy in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (1.0.0)
    Requirement already satisfied: uvicorn>=0.14.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.39.0)
    Requirement already satisfied: httpx>=0.24.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.28.1)
    Requirement already satisfied: pydub in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.25.1)
    Requirement already satisfied: tomlkit==0.12.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.12.0)
    Requirement already satisfied: typing-extensions~=4.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (4.16.0)
    Requirement already satisfied: orjson~=3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (3.11.5)
    Requirement already satisfied: urllib3~=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (2.6.3)
    Requirement already satisfied: huggingface-hub>=0.19.3 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.25.2)
    Requirement already satisfied: pydantic>=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (2.13.5)
    Requirement already satisfied: pandas<3.0,>=1.0 in c:\programdata\anaconda3\lib\site-packages (from gradio==4.44.1) (1.4.2)
    Requirement already satisfied: typer<1.0,>=0.12 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.23.2)
    Requirement already satisfied: pyyaml<7.0,>=5.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (6.0.3)
    Requirement already satisfied: numpy<3.0,>=1.0 in c:\programdata\anaconda3\lib\site-packages (from gradio==4.44.1) (1.21.5)
    Requirement already satisfied: ruff>=0.2.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.17.0)
    Requirement already satisfied: semantic-version~=2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (2.10.0)
    Requirement already satisfied: jinja2<4.0 in c:\programdata\anaconda3\lib\site-packages (from gradio==4.44.1) (2.11.3)
    Requirement already satisfied: fastapi<1.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.128.8)
    Requirement already satisfied: aiofiles<24.0,>=22.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (23.2.1)
    Collecting gradio-client==1.3.0
      Using cached gradio_client-1.3.0-py3-none-any.whl (318 kB)
    Requirement already satisfied: packaging in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (26.3)
    Requirement already satisfied: pillow<11.0,>=8.0 in c:\programdata\anaconda3\lib\site-packages (from gradio==4.44.1) (9.0.1)
    Requirement already satisfied: python-multipart>=0.0.9 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (0.0.20)
    Requirement already satisfied: anyio<5.0,>=3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio==4.44.1) (4.12.1)
    Requirement already satisfied: matplotlib~=3.0 in c:\programdata\anaconda3\lib\site-packages (from gradio==4.44.1) (3.5.1)
    Requirement already satisfied: fsspec in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio-client==1.3.0->gradio==4.44.1) (2025.10.0)Note: you may need to restart the kernel to use updated packages.
    
    Requirement already satisfied: websockets<13.0,>=10.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from gradio-client==1.3.0->gradio==4.44.1) (12.0)
    Requirement already satisfied: exceptiongroup>=1.0.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from anyio<5.0,>=3.0->gradio==4.44.1) (1.3.1)
    Requirement already satisfied: idna>=2.8 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from anyio<5.0,>=3.0->gradio==4.44.1) (3.20)
    Requirement already satisfied: typing-inspection>=0.4.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio==4.44.1) (0.4.2)
    

      WARNING: The scripts gradio.exe and upload_theme.exe are installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
    

    Requirement already satisfied: starlette<1.0.0,>=0.40.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio==4.44.1) (0.49.3)
    Requirement already satisfied: annotated-doc>=0.0.2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from fastapi<1.0->gradio==4.44.1) (0.0.5)
    Requirement already satisfied: httpcore==1.* in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpx>=0.24.1->gradio==4.44.1) (1.0.9)
    Requirement already satisfied: certifi in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpx>=0.24.1->gradio==4.44.1) (2026.7.22)
    Requirement already satisfied: h11>=0.16 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from httpcore==1.*->httpx>=0.24.1->gradio==4.44.1) (0.16.0)
    Requirement already satisfied: tqdm>=4.42.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio==4.44.1) (4.70.1)
    Requirement already satisfied: filelock in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio==4.44.1) (3.19.1)
    Requirement already satisfied: requests in c:\users\24108224\appdata\roaming\python\python39\site-packages (from huggingface-hub>=0.19.3->gradio==4.44.1) (2.32.5)
    Requirement already satisfied: zipp>=3.1.0 in c:\programdata\anaconda3\lib\site-packages (from importlib-resources<7.0,>=1.3->gradio==4.44.1) (3.7.0)
    Requirement already satisfied: kiwisolver>=1.0.1 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio==4.44.1) (1.3.2)
    Requirement already satisfied: python-dateutil>=2.7 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio==4.44.1) (2.8.2)
    Requirement already satisfied: fonttools>=4.22.0 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio==4.44.1) (4.25.0)
    Requirement already satisfied: pyparsing>=2.2.1 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio==4.44.1) (3.0.4)
    Requirement already satisfied: cycler>=0.10 in c:\programdata\anaconda3\lib\site-packages (from matplotlib~=3.0->gradio==4.44.1) (0.11.0)
    Requirement already satisfied: pytz>=2020.1 in c:\programdata\anaconda3\lib\site-packages (from pandas<3.0,>=1.0->gradio==4.44.1) (2021.3)
    Requirement already satisfied: annotated-types>=0.6.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from pydantic>=2.0->gradio==4.44.1) (0.7.0)
    Requirement already satisfied: pydantic-core==2.46.5 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from pydantic>=2.0->gradio==4.44.1) (2.46.5)
    Requirement already satisfied: six>=1.5 in c:\programdata\anaconda3\lib\site-packages (from python-dateutil>=2.7->matplotlib~=3.0->gradio==4.44.1) (1.16.0)
    Requirement already satisfied: colorama in c:\users\24108224\appdata\roaming\python\python39\site-packages (from tqdm>=4.42.1->huggingface-hub>=0.19.3->gradio==4.44.1) (0.4.6)
    Requirement already satisfied: click>=8.0.0 in c:\programdata\anaconda3\lib\site-packages (from typer<1.0,>=0.12->gradio==4.44.1) (8.0.4)
    Requirement already satisfied: rich>=12.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from typer<1.0,>=0.12->gradio==4.44.1) (15.0.0)
    Requirement already satisfied: shellingham>=1.3.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from typer<1.0,>=0.12->gradio==4.44.1) (1.5.4)
    Requirement already satisfied: markdown-it-py>=2.2.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from rich>=12.3.0->typer<1.0,>=0.12->gradio==4.44.1) (3.0.0)
    Requirement already satisfied: pygments<3.0.0,>=2.13.0 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from rich>=12.3.0->typer<1.0,>=0.12->gradio==4.44.1) (2.21.0)
    Requirement already satisfied: mdurl~=0.1 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from markdown-it-py>=2.2.0->rich>=12.3.0->typer<1.0,>=0.12->gradio==4.44.1) (0.1.2)
    Requirement already satisfied: charset_normalizer<4,>=2 in c:\users\24108224\appdata\roaming\python\python39\site-packages (from requests->huggingface-hub>=0.19.3->gradio==4.44.1) (3.5.2)
    Installing collected packages: gradio-client, gradio
    Successfully installed gradio-4.44.1 gradio-client-1.3.0
    


```python

```


```python

```


```python
import traceback

try:
    import gradio as gr
    print("Gradio version:", gr.__version__)
except Exception:
    traceback.print_exc()
```

    Gradio version: 4.44.1
    


```python
%pip install --force-reinstall "huggingface-hub==0.25.2"
```

    Defaulting to user installation because normal site-packages is not writeable
    Collecting huggingface-hub==0.25.2
      Using cached huggingface_hub-0.25.2-py3-none-any.whl (436 kB)
    Collecting requests
      Using cached requests-2.32.5-py3-none-any.whl (64 kB)
    Collecting filelock
      Using cached filelock-3.19.1-py3-none-any.whl (15 kB)
    Collecting pyyaml>=5.1
      Using cached pyyaml-6.0.3-cp39-cp39-win_amd64.whl (158 kB)
    Collecting tqdm>=4.42.1
      Using cached tqdm-4.70.1-py3-none-any.whl (80 kB)
    Collecting packaging>=20.9
      Using cached packaging-26.3-py3-none-any.whl (129 kB)
    Collecting typing-extensions>=3.7.4.3
      Using cached typing_extensions-4.16.0-py3-none-any.whl (45 kB)
    Collecting fsspec>=2023.5.0
      Using cached fsspec-2025.10.0-py3-none-any.whl (200 kB)
    Collecting colorama
      Using cached colorama-0.4.6-py2.py3-none-any.whl (25 kB)
    Collecting idna<4,>=2.5
      Using cached idna-3.20-py3-none-any.whl (69 kB)
    Collecting certifi>=2017.4.17
      Using cached certifi-2026.7.22-py3-none-any.whl (136 kB)
    Collecting charset_normalizer<4,>=2
      Using cached charset_normalizer-3.5.2-cp39-cp39-win_amd64.whl (215 kB)
    Collecting urllib3<3,>=1.21.1
      Using cached urllib3-2.6.3-py3-none-any.whl (131 kB)
    Installing collected packages: urllib3, idna, colorama, charset-normalizer, certifi, typing-extensions, tqdm, requests, pyyaml, packaging, fsspec, filelock, huggingface-hub
      Attempting uninstall: urllib3
        Found existing installation: urllib3 2.6.3
        Uninstalling urllib3-2.6.3:
          Successfully uninstalled urllib3-2.6.3
      Attempting uninstall: idna
        Found existing installation: idna 3.20
        Uninstalling idna-3.20:
          Successfully uninstalled idna-3.20
      Attempting uninstall: colorama
        Found existing installation: colorama 0.4.6
        Uninstalling colorama-0.4.6:
          Successfully uninstalled colorama-0.4.6
      Attempting uninstall: charset-normalizer
        Found existing installation: charset-normalizer 3.5.2
        Uninstalling charset-normalizer-3.5.2:
          Successfully uninstalled charset-normalizer-3.5.2
    Note: you may need to restart the kernel to use updated packages.
    

      WARNING: The script idna.exe is installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
      WARNING: The script normalizer.exe is installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
    ERROR: Could not install packages due to an OSError: [WinError 5] Access is denied: 'C:\\Users\\24108224\\AppData\\Roaming\\Python\\Python39\\site-packages\\~harset_normalizer\\cd.cp39-win_amd64.pyd'
    Check the permissions.
    
    


```python
import gradio as gr

print("Gradio is working!")
print("Version:", gr.__version__)
```


    ---------------------------------------------------------------------------

    ImportError                               Traceback (most recent call last)

    Input In [11], in <cell line: 1>()
    ----> 1 import gradio as gr
          3 print("Gradio is working!")
          4 print("Version:", gr.__version__)
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\__init__.py:3, in <module>
          1 import json
    ----> 3 import gradio._simple_templates
          4 import gradio.image_utils
          5 import gradio.processing_utils
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\_simple_templates\__init__.py:1, in <module>
    ----> 1 from .simpledropdown import SimpleDropdown
          2 from .simpleimage import SimpleImage
          3 from .simpletextbox import SimpleTextbox
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\_simple_templates\simpledropdown.py:6, in <module>
          3 import warnings
          4 from typing import TYPE_CHECKING, Any, Callable, Sequence
    ----> 6 from gradio.components.base import Component, FormComponent
          7 from gradio.events import Events
          9 if TYPE_CHECKING:
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\components\__init__.py:1, in <module>
    ----> 1 from gradio.components.annotated_image import AnnotatedImage
          2 from gradio.components.audio import Audio
          3 from gradio.components.base import (
          4     Component,
          5     FormComponent,
       (...)
         10     get_component_instance,
         11 )
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\components\annotated_image.py:14, in <module>
         11 from gradio_client.documentation import document
         13 from gradio import processing_utils, utils
    ---> 14 from gradio.components.base import Component
         15 from gradio.data_classes import FileData, GradioModel
         16 from gradio.events import Events
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\components\base.py:20, in <module>
         17 import gradio_client.utils as client_utils
         19 from gradio import utils
    ---> 20 from gradio.blocks import Block, BlockContext
         21 from gradio.component_meta import ComponentMeta
         22 from gradio.data_classes import BaseModel, DeveloperPath, GradioDataModel
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\blocks.py:39, in <module>
         36 from gradio_client import utils as client_utils
         37 from gradio_client.documentation import document
    ---> 39 from gradio import (
         40     analytics,
         41     components,
         42     networking,
         43     processing_utils,
         44     queueing,
         45     routes,
         46     strings,
         47     themes,
         48     utils,
         49     wasm_utils,
         50 )
         51 from gradio.blocks_events import BlocksEvents, BlocksMeta
         52 from gradio.context import (
         53     Context,
         54     LocalContext,
       (...)
         57     set_render_context,
         58 )
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\networking.py:15, in <module>
         11 import warnings
         13 import httpx
    ---> 15 from gradio.routes import App  # HACK: to avoid circular import # noqa: F401
         16 from gradio.tunneling import Tunnel
         18 GRADIO_API_SERVER = "https://api.gradio.app/v2/tunnel-request"
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\routes.py:69, in <module>
         66 from starlette.responses import RedirectResponse, StreamingResponse
         68 import gradio
    ---> 69 from gradio import ranged_response, route_utils, utils, wasm_utils
         70 from gradio.context import Context
         71 from gradio.data_classes import (
         72     CancelBody,
         73     ComponentServerBlobBody,
       (...)
         81     UserProvidedPath,
         82 )
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\route_utils.py:53, in <module>
         47 from gradio.data_classes import (
         48     BlocksConfigDict,
         49     PredictBody,
         50     PredictBodyInternal,
         51 )
         52 from gradio.exceptions import Error
    ---> 53 from gradio.helpers import EventData
         54 from gradio.state_holder import SessionState
         56 if TYPE_CHECKING:
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\helpers.py:26, in <module>
         23 from gradio_client import utils as client_utils
         24 from gradio_client.documentation import document
    ---> 26 from gradio import components, oauth, processing_utils, routes, utils, wasm_utils
         27 from gradio.context import Context, LocalContext, get_blocks_context
         28 from gradio.data_classes import GradioModel, GradioRootModel
    

    File ~\AppData\Roaming\Python\Python39\site-packages\gradio\oauth.py:13, in <module>
         11 import fastapi
         12 from fastapi.responses import RedirectResponse
    ---> 13 from huggingface_hub import HfFolder, whoami
         15 from .utils import get_space
         17 OAUTH_CLIENT_ID = os.environ.get("OAUTH_CLIENT_ID")
    

    ImportError: cannot import name 'HfFolder' from 'huggingface_hub' (C:\Users\24108224\AppData\Roaming\Python\Python39\site-packages\huggingface_hub\__init__.py)



```python
%pip install --force-reinstall "huggingface-hub==0.25.2"
```

    Defaulting to user installation because normal site-packages is not writeable
    Collecting huggingface-hub==0.25.2
      Using cached huggingface_hub-0.25.2-py3-none-any.whl (436 kB)
    Collecting fsspec>=2023.5.0
      Using cached fsspec-2025.10.0-py3-none-any.whl (200 kB)
    Collecting packaging>=20.9
      Using cached packaging-26.3-py3-none-any.whl (129 kB)
    Collecting tqdm>=4.42.1
      Using cached tqdm-4.70.1-py3-none-any.whl (80 kB)
    Collecting typing-extensions>=3.7.4.3
      Using cached typing_extensions-4.16.0-py3-none-any.whl (45 kB)
    Collecting requests
      Using cached requests-2.32.5-py3-none-any.whl (64 kB)
    Collecting filelock
      Using cached filelock-3.19.1-py3-none-any.whl (15 kB)
    Collecting pyyaml>=5.1
      Using cached pyyaml-6.0.3-cp39-cp39-win_amd64.whl (158 kB)
    Collecting colorama
      Using cached colorama-0.4.6-py2.py3-none-any.whl (25 kB)
    Collecting certifi>=2017.4.17
      Using cached certifi-2026.7.22-py3-none-any.whl (136 kB)
    Collecting urllib3<3,>=1.21.1
      Using cached urllib3-2.6.3-py3-none-any.whl (131 kB)Note: you may need to restart the kernel to use updated packages.
    

      WARNING: The script idna.exe is installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
      WARNING: The script normalizer.exe is installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
      WARNING: The script tqdm.exe is installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
      WARNING: The script huggingface-cli.exe is installed in 'C:\Users\24108224\AppData\Roaming\Python\Python39\Scripts' which is not on PATH.
      Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
    ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
    conda-repo-cli 1.0.4 requires pathlib, which is not installed.
    jupyter-server 1.13.5 requires anyio<4,>=3.1.0, but you have anyio 4.12.1 which is incompatible.
    jupyter-server 1.13.5 requires pywinpty<2; os_name == "nt", but you have pywinpty 2.0.2 which is incompatible.
    botocore 1.24.32 requires urllib3<1.27,>=1.25.4, but you have urllib3 2.6.3 which is incompatible.
    aiohttp 3.8.1 requires charset-normalizer<3.0,>=2.0, but you have charset-normalizer 3.5.2 which is incompatible.
    

    
    Collecting idna<4,>=2.5
      Using cached idna-3.20-py3-none-any.whl (69 kB)
    Collecting charset_normalizer<4,>=2
      Using cached charset_normalizer-3.5.2-cp39-cp39-win_amd64.whl (215 kB)
    Installing collected packages: urllib3, idna, colorama, charset-normalizer, certifi, typing-extensions, tqdm, requests, pyyaml, packaging, fsspec, filelock, huggingface-hub
      Attempting uninstall: urllib3
        Found existing installation: urllib3 2.6.3
        Uninstalling urllib3-2.6.3:
          Successfully uninstalled urllib3-2.6.3
      Attempting uninstall: idna
        Found existing installation: idna 3.20
        Uninstalling idna-3.20:
          Successfully uninstalled idna-3.20
      Attempting uninstall: colorama
        Found existing installation: colorama 0.4.6
        Uninstalling colorama-0.4.6:
          Successfully uninstalled colorama-0.4.6
      Attempting uninstall: charset-normalizer
        Found existing installation: charset-normalizer 3.5.2
        Uninstalling charset-normalizer-3.5.2:
          Successfully uninstalled charset-normalizer-3.5.2
      Attempting uninstall: certifi
        Found existing installation: certifi 2026.7.22
        Uninstalling certifi-2026.7.22:
          Successfully uninstalled certifi-2026.7.22
      Attempting uninstall: typing-extensions
        Found existing installation: typing-extensions 4.16.0
        Uninstalling typing-extensions-4.16.0:
          Successfully uninstalled typing-extensions-4.16.0
      Attempting uninstall: tqdm
        Found existing installation: tqdm 4.70.1
        Uninstalling tqdm-4.70.1:
          Successfully uninstalled tqdm-4.70.1
      Attempting uninstall: requests
        Found existing installation: requests 2.32.5
        Uninstalling requests-2.32.5:
          Successfully uninstalled requests-2.32.5
      Attempting uninstall: pyyaml
        Found existing installation: pyyaml 6.0.3
        Uninstalling pyyaml-6.0.3:
          Successfully uninstalled pyyaml-6.0.3
      Attempting uninstall: packaging
        Found existing installation: packaging 26.3
        Uninstalling packaging-26.3:
          Successfully uninstalled packaging-26.3
      Attempting uninstall: fsspec
        Found existing installation: fsspec 2025.10.0
        Uninstalling fsspec-2025.10.0:
          Successfully uninstalled fsspec-2025.10.0
      Attempting uninstall: filelock
        Found existing installation: filelock 3.19.1
        Uninstalling filelock-3.19.1:
          Successfully uninstalled filelock-3.19.1
      Attempting uninstall: huggingface-hub
        Found existing installation: huggingface-hub 0.25.2
        Uninstalling huggingface-hub-0.25.2:
          Successfully uninstalled huggingface-hub-0.25.2
    Successfully installed certifi-2026.7.22 charset-normalizer-3.5.2 colorama-0.4.6 filelock-3.19.1 fsspec-2025.10.0 huggingface-hub-0.25.2 idna-3.20 packaging-26.3 pyyaml-6.0.3 requests-2.32.5 tqdm-4.70.1 typing-extensions-4.16.0 urllib3-2.6.3
    


```python
import gradio as gr
import huggingface_hub

print("Gradio:", gr.__version__)
print("Hugging Face Hub:", huggingface_hub.__version__)
print("Both packages imported successfully!")
```

    Gradio: 4.44.1
    Hugging Face Hub: 0.25.2
    Both packages imported successfully!
    


```python
import gradio as gr
import pandas as pd
import sklearn
import flask

print("Gradio:", gr.__version__)
print("All libraries imported successfully!")
```

    Gradio: 4.44.1
    All libraries imported successfully!
    


```python
import gradio as gr

# Function for salary prediction
def predict_salary(years_experience, education):
    data = pd.DataFrame([{
        "Years_Experience": years_experience,
        "Education": education
    }])

    prediction = salary_model.predict(data)[0]
    probabilities = salary_model.predict_proba(data)[0]

    result = f"Predicted Salary Level: {prediction}"

    for label, probability in zip(
        salary_model.classes_, probabilities
    ):
        result += f"\n{label}: {probability:.2%}"

    return result


# Function for student prediction
def predict_student(study_hours, attendance, previous_score):
    data = pd.DataFrame([{
        "Study_Hours": study_hours,
        "Attendance_Pct": attendance,
        "Previous_Score": previous_score
    }])

    prediction = student_model.predict(data)[0]
    probabilities = student_model.predict_proba(data)[0]

    result = f"Predicted Student Result: {prediction}"

    for label, probability in zip(
        student_model.classes_, probabilities
    ):
        result += f"\n{label}: {probability:.2%}"

    return result


# Salary interface
salary_interface = gr.Interface(
    fn=predict_salary,
    inputs=[
        gr.Number(label="Years of Experience", value=3),
        gr.Dropdown(
            choices=sorted(salary_df["Education"].unique().tolist()),
            label="Education"
        )
    ],
    outputs=gr.Textbox(label="Prediction"),
    title="Salary Level Prediction",
    description="Predict salary category using Logistic Regression."
)


# Student interface
student_interface = gr.Interface(
    fn=predict_student,
    inputs=[
        gr.Number(label="Study Hours", value=5),
        gr.Number(label="Attendance Percentage", value=80),
        gr.Number(label="Previous Score", value=60)
    ],
    outputs=gr.Textbox(label="Prediction"),
    title="Student Result Prediction",
    description="Predict Pass or Fail using Logistic Regression."
)

print("Both Gradio interfaces are ready.")
```

    Both Gradio interfaces are ready.
    


```python
salary_interface.launch(
    share=False,
    prevent_thread_lock=True
)
```

    Running on local URL:  http://127.0.0.1:7860
    
    To create a public link, set `share=True` in `launch()`.
    


<div><iframe src="http://127.0.0.1:7860/" width="100%" height="500" allow="autoplay; camera; microphone; clipboard-read; clipboard-write;" frameborder="0" allowfullscreen></iframe></div>





    




```python
from flask import Flask, request, render_template_string
from threading import Thread

app = Flask(__name__)

# Common HTML template
page = """
<!DOCTYPE html>
<html>
<head>
    <title>Logistic Regression Prediction</title>
    <style>
        body {
            font-family: Arial;
            max-width: 600px;
            margin: 40px auto;
            padding: 20px;
            background: #f4f4f4;
        }
        form, .result {
            background: white;
            padding: 20px;
            border-radius: 10px;
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin: 8px 0 15px;
            box-sizing: border-box;
        }
        button {
            background: #1769aa;
            color: white;
            border: none;
            cursor: pointer;
        }
        a {
            margin-right: 15px;
        }
    </style>
</head>
<body>
    <h1>Classification Prediction</h1>

    <a href="/">Home</a>
    <a href="/salary">Salary Model</a>
    <a href="/student">Student Model</a>

    <h2>{{ title }}</h2>

    <form method="POST">
        {{ form_fields|safe }}
        <button type="submit">Predict</button>
    </form>

    {% if result %}
    <div class="result">
        <h3>Prediction Result</h3>
        <pre>{{ result }}</pre>
    </div>
    {% endif %}
</body>
</html>
"""


@app.route("/")
def home():
    return """
    <h1>Logistic Regression Project</h1>
    <p><a href="/salary">Salary Classification</a></p>
    <p><a href="/student">Student Result Classification</a></p>
    """


# Salary prediction page
@app.route("/salary", methods=["GET", "POST"])
def salary_page():
    result = ""

    education_options = "".join(
        f'<option value="{e}">{e}</option>'
        for e in sorted(salary_df["Education"].unique())
    )

    fields = f"""
    <label>Years of Experience</label>
    <input type="number" name="experience"
           min="0" step="any" value="3" required>

    <label>Education</label>
    <select name="education" required>
        {education_options}
    </select>
    """

    if request.method == "POST":
        experience = float(request.form["experience"])
        education = request.form["education"]

        data = pd.DataFrame([{
            "Years_Experience": experience,
            "Education": education
        }])

        prediction = salary_model.predict(data)[0]
        probabilities = salary_model.predict_proba(data)[0]

        result = f"Predicted Salary Level: {prediction}\n"

        for label, probability in zip(
            salary_model.classes_, probabilities
        ):
            result += f"{label}: {probability:.2%}\n"

    return render_template_string(
        page,
        title="Salary Level Prediction",
        form_fields=fields,
        result=result
    )


# Student prediction page
@app.route("/student", methods=["GET", "POST"])
def student_page():
    result = ""

    fields = """
    <label>Study Hours</label>
    <input type="number" name="hours"
           min="0" step="any" value="5" required>

    <label>Attendance Percentage</label>
    <input type="number" name="attendance"
           min="0" max="100" step="any" value="80" required>

    <label>Previous Score</label>
    <input type="number" name="score"
           min="0" max="100" step="any" value="60" required>
    """

    if request.method == "POST":
        hours = float(request.form["hours"])
        attendance = float(request.form["attendance"])
        score = float(request.form["score"])

        data = pd.DataFrame([{
            "Study_Hours": hours,
            "Attendance_Pct": attendance,
            "Previous_Score": score
        }])

        prediction = student_model.predict(data)[0]
        probabilities = student_model.predict_proba(data)[0]

        result = f"Predicted Student Result: {prediction}\n"

        for label, probability in zip(
            student_model.classes_, probabilities
        ):
            result += f"{label}: {probability:.2%}\n"

    return render_template_string(
        page,
        title="Student Result Prediction",
        form_fields=fields,
        result=result
    )


print("Flask application is ready.")
```

    Flask application is ready.
    


```python
def run_flask():
    app.run(
        host="127.0.0.1",
        port=5000,
        debug=False,
        use_reloader=False
    )

flask_thread = Thread(target=run_flask, daemon=True)
flask_thread.start()

print("Open this address in your browser:")
print("http://127.0.0.1:5000")
```

    Open this address in your browser:
    http://127.0.0.1:5000
     * Serving Flask app "__main__" (lazy loading)
     * Environment: production
    [31m   WARNING: This is a development server. Do not use it in a production deployment.[0m
    [2m   Use a production WSGI server instead.[0m
     * Debug mode: off
    

     * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
    127.0.0.1 - - [14/Oct/2026 14:59:11] "GET / HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 14:59:11] "GET /favicon.ico HTTP/1.1" 404 -
    127.0.0.1 - - [14/Oct/2026 14:59:15] "GET /salary HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 14:59:20] "POST /salary HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 14:59:22] "GET / HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 14:59:23] "GET /student HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 14:59:25] "POST /student HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 14:59:28] "GET / HTTP/1.1" 200 -
    


```python
import joblib

joblib.dump(salary_model, "salary_model.pkl")
joblib.dump(student_model, "student_model.pkl")

print("Both models saved successfully!")
```

    Both models saved successfully!
    

    127.0.0.1 - - [14/Oct/2026 15:03:17] "GET / HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 15:03:19] "GET /salary HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 15:26:16] "GET / HTTP/1.1" 200 -
    127.0.0.1 - - [14/Oct/2026 15:26:18] "GET /salary HTTP/1.1" 200 -
    


```python

```
