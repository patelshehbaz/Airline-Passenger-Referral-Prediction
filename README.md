# Airline Passenger Referral Prediction

## Project Overview

This project aims to predict whether a passenger referred by an existing customer will book a flight or not. The model is built using machine learning classification techniques and takes into account various features such as seat comfort, cabin service, travel class, food and beverage service, entertainment, and more. The outcome helps airlines target potential passengers with marketing campaigns based on referrals from existing customers.

The dataset includes airline reviews from 2016 to 2019 for popular airlines worldwide, combining multiple-choice and free-text responses. The data was scraped in Spring 2019. The primary goal is to predict whether passengers will recommend the airline to their friends.

## How to Run the Project

1. Clone the repository:

```bash
   git clone <repo-link>
   cd <repo-directory>
```

2. Create a virtual environment:

```
conda create -p venv python=3.9 -y
```

3. Activate the virtual environment:

```
conda activate venv
```

4. Install dependencies:

```
pip install -r requirements.txt
```

5. Run the Gradio interface:

```
python app.py
```

6. Deactivate the environment when done:

```
conda deactivate
```

## Tech Stack

- Python: Core programming language used.
- Machine Learning: For building the predictive model.
- Azure: Used as the database to store and manage data.
- Gradio: Interactive UI for model prediction.
