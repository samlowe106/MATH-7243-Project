# MATH-7243-Project

## Setup

1. Create a Python 3.11 virtual environment at the `PATH` of your choice by running `python3.11 -m venv PATH`. Ensure that `PATH` is included the .gitignore file.
2. Activate your virtual environment by running `source PATH/bin/activate`
3. Update pip by running `python3.11 -m pip install --upgrade pip`
4. Install the project requirements by running `pip install -r requirements.txt`
5. Install pre-commit hooks for this repo by running `pre-commit install`

## Dataset

The dataset was uploaded by Meir Nizri to Kaggle and can be found at https://www.kaggle.com/datasets/meirnizri/covid19-dataset

This data represents the medical characteristics of anonymous COVID patients; there are 21 unique features and 1,048,576 unique patients. The features and their encodings are described on Kaggle as follows:

- sex: 1 for female and 2 for male.
- age: of the patient.
- classification: covid test findings. Values 1-3 mean that the patient was diagnosed with covid in different
- degrees. 4 or higher means that the patient is not a carrier of covid or that the test is inconclusive.
- patient type: type of care the patient received in the unit. 1 for returned home and 2 for hospitalization.
- pneumonia: whether the patient already have air sacs inflammation or not.
- pregnancy: whether the patient is pregnant or not.
- diabetes: whether the patient has diabetes or not.
- copd: Indicates whether the patient has Chronic obstructive pulmonary disease or not.
- asthma: whether the patient has asthma or not.
- inmsupr: whether the patient is immunosuppressed or not.
- hypertension: whether the patient has hypertension or not.
- cardiovascular: whether the patient has heart or blood vessels related disease.
- renal chronic: whether the patient has chronic renal disease or not.
- other disease: whether the patient has other disease or not.
- obesity: whether the patient is obese or not.
- tobacco: whether the patient is a tobacco user.
- usmr: Indicates whether the patient treated medical units of the first, second or third level.
- medical unit: type of institution of the National Health System that provided the care.
- intubed: whether the patient was connected to the ventilator.
- icu: Indicates whether the patient had been admitted to an Intensive Care Unit.
- date died: If the patient died indicate the date of death, and 9999-99-99 otherwise.

Where 1 means "yes" and 2 means "no" for boolean features, and values such as 97 and 99 represent missing data.

The dataset is licensed under Creative Commons.
