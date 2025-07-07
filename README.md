# Steam Sales Data Analysis and Prediction

This repository contains my **CS210 final project**: analyzing Steam game sales data with data cleaning, EDA, machine learning predictions, PostgreSQL database storage, and visual reporting.

---

## Overview

- **Data Source:** SteamSpy top 100 games dataset.
- **Data Cleaning:** Removes invalid entries, handles missing data, adds calculated fields.
- **EDA:** Generates price and discount distribution plots and top discounted games lists.
- **Machine Learning:** Trains Linear Regression and Random Forest models to predict game prices.
- **Model Improvement:** Uses GridSearchCV to tune the Random Forest model for better accuracy.
- **Database:** Stores cleaned data and model outputs in a PostgreSQL database.
- **SQL:** Runs example queries for insights.

---

## Project Structure

steam_project/
│
├── data/ # Raw dataset
├── cleaned_data/ # Cleaned CSV and EDA plots
├── ml_output/ # Baseline ML outputs
├── ml_output_improved/ # Improved RF model outputs
├── src/ # Python source code files
├── create_tables.sql # SQL schema for database
├── config.ini # DB connection info
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## Tech Stack

- **Python 3.9+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `psycopg2-binary`, `configparser`
- **PostgreSQL**
- **Git & GitHub**

---

## Run the Project

1. **Clone this repo:**

   ```bash
   git clone https://github.com/Musaborhan27/Steam-Sales-Data-Analysis-and-Prediction.git

2. **Create a virtual environment:

- python3 -m venv venv
- source venv/bin/activate

3. **Install dependencies:

- pip install -r requirements.txt

4. **Set up your PostgreSQL database:

- Create a database.
- Update config.ini with your database name, user, password, host, and port.

5. Run the main pipeline:

- python src/main.py


