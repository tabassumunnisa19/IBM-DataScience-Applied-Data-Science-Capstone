# 🚀 SpaceX Launch Analysis & Prediction  
### IBM Applied Data Science Capstone Project

## 📌 Project Overview
This project is the **final capstone project** of the **IBM Data Science Professional Certificate** on Coursera.  
The goal of the project is to **analyze SpaceX Falcon 9 launch data**, identify key factors affecting launch success, and **build predictive machine learning models** to estimate whether a rocket launch will land successfully.

SpaceX significantly reduces launch costs by reusing the first stage. Accurately predicting landing success can help competitors estimate launch costs and improve decision-making.

---

## 🎯 Problem Statement
- Can we predict whether a **Falcon 9 first stage will successfully land**?
- What factors influence launch success?
- How do payload mass, launch site, orbit type, and booster version affect outcomes?

---

## 🧰 Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
  - Plotly, Dash  
  - Scikit-learn  
  - SQL (SQLite)  
- **Visualization:** Plotly Dash, Folium Maps  
- **Machine Learning Models:**  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Decision Tree Classifier  
  - K-Nearest Neighbors (KNN)  
- **Deployment & Reporting:**  
  - Jupyter Notebooks  
  - GitHub  
  - Dash Interactive Dashboard  

---

## 📂 Project Structure

---

## 📁 Project Structure

```text
├── data_collection/
│   ├── jupyter-labs-spacex-data-collection-api.ipynb
│   ├── jupyter-labs-webscraping.ipynb
│
├── data_wrangling/
│   ├── labs-jupyter-spacex-Data wrangling.ipynb
│
├── exploratory_data_analysis/
│   ├── jupyter-labs-eda-sql-coursera_sqllite.ipynb
│   ├── edadataviz.ipynb
│
├── interactive_visualization/
│   ├── lab_jupyter_launch_site_location.ipynb
│   ├── spacex_dash_app.py
│
├── machine_learning/
│   ├── SpaceX_Machine Learning Prediction_Part_5.ipynb
│
├── README.md
```






---

## 📊 Project Workflow

### 1️⃣ Data Collection
- Collected SpaceX launch data using:
  - **SpaceX REST API**
  - **Web scraping** from Wikipedia
- Extracted information such as:
  - Launch sites
  - Payload mass
  - Orbit type
  - Booster version
  - Landing outcome

---

### 2️⃣ Data Wrangling
- Cleaned missing and inconsistent values
- Converted categorical variables
- Created target variable (`Class`):
  - `1` → Successful landing  
  - `0` → Failed landing  

---

### 3️⃣ Exploratory Data Analysis (EDA)
- SQL-based exploration using SQLite
- Statistical analysis and visualization
- Identified patterns in:
  - Payload vs Success
  - Launch site vs Success
  - Orbit vs Success
  - Booster version vs Success

---

### 4️⃣ Interactive Data Visualization
- **Folium maps** to visualize launch sites and success rates
- **Plotly Dash Dashboard**:
  - Launch site dropdown
  - Payload range slider
  - Success vs Failure pie chart
  - Payload vs Success scatter plot
- Fully interactive web dashboard for exploration

---

### 5️⃣ Machine Learning Modeling
- Feature scaling using **StandardScaler**
- Train-test split (80% / 20%)
- Hyperparameter tuning using **GridSearchCV**
- Models implemented:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - K-Nearest Neighbors (KNN)

---

### 6️⃣ Model Evaluation
- Accuracy comparison across models
- Confusion matrix analysis
- Validation and test performance evaluation
- Identified best-performing model based on accuracy and generalization

---

## 🏆 Results & Insights
- Payload mass and launch site strongly influence success
- Certain booster versions have higher success rates
- Machine learning models achieved **high prediction accuracy**
- Logistic Regression and SVM showed strong performance with proper tuning

---

## 📈 Dashboard Preview
The project includes an **interactive Plotly Dash dashboard** that allows users to:
- Select launch sites
- Adjust payload range
- Visualize success rates dynamically
- Analyze payload vs landing outcome

---

## 🔮 Future Improvements
- Integrate real-time SpaceX API updates
- Deploy dashboard using cloud platforms
- Add deep learning models
- Enhance feature engineering
- Improve class imbalance handling

---

## 🧠 Key Learnings
- End-to-end data science workflow
- API & web scraping techniques
- SQL + Python integration
- Interactive dashboard development
- Model selection and hyperparameter tuning
- Real-world predictive analytics

---

## 📜 Certification
This project is part of:
**IBM Data Science Professional Certificate**  
offered via **Coursera**
 

---

## ⭐ Acknowledgements
- IBM Skills Network  
- Coursera  
- SpaceX public data  
- Open-source Python community  

---

## 📎 License
---

This project is licensed under the **MIT License**.

It is created for **educational purposes** as part of the  
**IBM Applied Data Science Capstone Project** on Coursera.

You are free to:
- Use the code for learning and personal projects
- Modify and adapt the code with proper attribution

Commercial use of the project results or datasets should comply with
the respective data source licenses (e.g., SpaceX public data).

---

