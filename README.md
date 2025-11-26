1️⃣ Project Title

Forest Fire Risk Prediction

2️⃣ Project Description

This project predicts forest fire occurrences using environmental data. It combines machine learning (PySpark Random Forest Classifier) for prediction with a Power BI dashboard for interactive visualization of forest fire risk patterns.

Key Goals:

Predict probability of forest fires based on environmental factors.

Visualize trends by month, location, and environmental features.

Provide actionable insights for forest management.

3️⃣ Features / Highlights

PySpark-based machine learning pipeline.

Handles missing data and categorical encoding.

Random Forest classifier for fire risk prediction.

Power BI dashboard with interactive charts and KPIs.

Visualizes patterns in temperature, humidity, wind, and fire indices.

4️⃣ Tech Stack / Tools

Programming Languages: Python (PySpark), SQL

Data Analysis & Visualization: Pandas, Matplotlib, Seaborn

Big Data Tools: Apache Spark

Dashboard: Power BI

Database: PostgreSQL / MySQL (optional)

Version Control: Git & GitHub

5️⃣ Dataset

Source: Forest Fire dataset (e.g., UCI or provided dataset)

Number of records: ~500

Features: X, Y, FFMC, DMC, DC, ISI, temp, RH, wind, rain, month, day

Target variable: fire_occurred (0 = no fire, 1 = fire)

6️⃣ Project Structure
Forest-Fire-Risk-Prediction/
│
├── source code of cluster project.txt    # PySpark ML code
├── Forest_Fire_Analysis.pbix             # Power BI dashboard
├── README.md                             # Project documentation
└── (any other supporting files)

7️⃣ Workflow / Steps

Data Preprocessing

Handled missing values in temp, RH, wind.

Encoded categorical features month and day.

Feature Engineering

Combined numeric and indexed features into a single feature vector using VectorAssembler.

Created binary target column fire_occurred.

Model Training

Split dataset into training (80%) and test (20%).

Trained a RandomForestClassifier using PySpark.

Model Evaluation

Accuracy: ~0.71

F1 Score: ~0.71

Visualization (Power BI Dashboard)

Interactive visuals for environmental trends, risk patterns, and KPIs.

Analyzed monthly, location-wise, and factor-wise trends.

8️⃣ How to Run

PySpark Model:

spark-submit "source code of cluster project.txt"


Power BI Dashboard:

Open Forest_Fire_Analysis.pbix in Power BI Desktop.

Explore interactive charts and KPIs.

9️⃣ Key Takeaways

End-to-end workflow: Data → Model → Visualization.

Predictive analytics with actionable insights.

Professional dashboard for monitoring forest fire risks.

10️⃣ GitHub Repository

Forest Fire Risk Prediction

11️⃣ Contact

Developer: Katherla Vijay Kumar
Email: vijaykumarkatherla1@gmail.com

LinkedIn:https://www.linkedin.com/in/katherla-vijay-kumar-566b76265/
