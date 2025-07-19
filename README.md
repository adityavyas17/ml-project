 🏏 IPL Win Predictor

A machine learning web app that predicts the probability of a team winning an IPL match based on match conditions. Built using **XGBoost**, trained on IPL match data from **Kaggle**, and deployed using **Render**.

---

## 🔗 Live App

👉 [Access the Web App on Render](https://ipl-win-predictor-q3p4.onrender.com/)  

---

## 📂 Project Structure

| File/Folder      | Description                                               |
|------------------|-----------------------------------------------------------|
| `app.py`         | Streamlit application code                                |
| `ipl.ipynb`      | Jupyter Notebook with model training using XGBoost        |
| `pipe.pkl`       | Serialized model pipeline file                            |
| `matches.csv`    | IPL match-level dataset from Kaggle                       |
| `deliveries.csv` | Ball-by-ball dataset from Kaggle                          |
| `requirements.txt` | Python dependencies for the app                         |
| `procfile`       | Process file required by Render to run the app           |
| `setup.sh`       | Setup script (if needed by Render for environment setup) |

---

## 📊 Dataset

- Data Source: [IPL Complete Dataset (2008-2024)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)  
- Includes:
  - Match info (teams, venue, result)
  - Ball-by-ball performance (runs, wickets, overs)
  - Target and chase conditions

---

## ⚙️ Model

- **Algorithm:** XGBoost Classifier
- **Objective:** Predict probability of batting team winning
- **Features Used:**
  - Batting team
  - Bowling team
  - Runs left
  - Balls left
  - Wickets left
  - Current Run Rate
  - Required Run Rate
  - Target Score
  - Venue
 
  ## 📸 Screenshot of the app deployed on Render

  <img width="1255" height="850" alt="image" src="https://github.com/user-attachments/assets/fe31e7d8-b12b-48ed-a952-01332f93fa50" />
