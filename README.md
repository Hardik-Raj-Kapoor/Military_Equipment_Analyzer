<h1> Military Equipment Analyzer – Predictive Maintenance in Defense </h1>
<h3>Overview</h3>
The Military Equipment Analyzer is a predictive maintenance system built using machine learning to assess the performance and readiness of mission-critical military assets such as Fighter Jets, Weapons, and Vehicles.
This project helps defense systems transition from reactive to proactive maintenance by using equipment data to predict performance and provide actionable insights on whether an asset should be maintained, monitored, or retired.


<h3>Problem Statement </h3>
In modern defense, equipment failure during critical missions can be catastrophic. Regular manual checks are labor-intensive and inefficient. Our goal is to:

1. Analyze performance data from military equipment

2. Predict operational status using classification models

3. Display insights through a user-friendly web dashboard


<h3>Machine Learning Models </h3>
We implemented and compared the following ML models:

1. Random Forest Classifier – Ensemble method that uses multiple decision trees.

2. Support Vector Machine (SVM) – Good for high-dimensional data with strong classification boundaries.


<h3>Data Description</h3>
Each equipment dataset includes parameters such as:

Type (Weapon / Jet / Vehicle)

Battalion Area

Temperature & Weather Conditions

Usage Hours

Failure Incidents

Performance Metrics


<h3>Datasets:</h3>
1. jets_data_updated.csv

2. guns_data_with_environment.csv

3. IEEE_DRDO_data.csv


<h3>Web Application</h3>
We built a Flask-based dashboard with a clean, responsive frontend.


<h3>Key Features:</h3>
i. Input Equipment ID to view current status

ii. Usage vs Performance visualizations

iii. Temperature & Environment analysis

iv. Light/Dark Mode Toggle

v. Separate category folders for each equipment type


<h3>How It Works (Workflow)</h3>
Data Ingestion – Load .csv files into pandas DataFrames

Preprocessing – Handle nulls, convert categories, scale values

Model Training – Train Random Forest and SVM models

Model Evaluation – Accuracy, Confusion Matrix, Precision, Recall

Flask Integration – Wrap model in app.py for prediction

Visualization – Render plots via matplotlib/seaborn


<h3>Future Enhancements</h3>
1. IoT Integration – Real-time sensor input from military assets

2. Live Dashboard – Continuous status updates from units

3. Federated Learning – Train across branches without sharing sensitive data

4. Multi-force Deployment – Extend to Army, Navy, and Air Force

<h3>Tech Stack</h3>
Python, pandas, numpy, scikit-learn

Flask

HTML, CSS, JS

MySQL (optional for data storage)

Jupyter Notebook, VS Code


<h3>Contributors</h3>
Sukalp Jhingran
Hardik Raj Kapoor
<h4>Mentor: Dr. Tanupriya Choudhury</h4>


<h3>License</h3>
This project is intended for academic demonstration purposes only. For external use, please contact the maintainers.
🔗 Stay Mission-Ready. Predict. Prevent. Perform.
