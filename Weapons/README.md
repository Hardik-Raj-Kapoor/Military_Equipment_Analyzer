<h1> Military Equipment Analyzer – Predictive Maintenance in Defense </h1>
**📘 Overview**
The Military Equipment Analyzer is a predictive maintenance system built using machine learning to assess the performance and readiness of mission-critical military assets such as Fighter Jets, Weapons, and Vehicles.
This project helps defense systems transition from reactive to proactive maintenance by using equipment data to predict performance and provide actionable insights on whether an asset should be maintained, monitored, or retired.

**🎯 Problem Statement**
In modern defense, equipment failure during critical missions can be catastrophic. Regular manual checks are labor-intensive and inefficient. Our goal is to:
- Analyze performance data from military equipment
- Predict operational status using classification models
- Display insights through a user-friendly web dashboard

**⚙️ Classification Labels**
Performance (%)	Status	Action
≥ 90%	✅ Good Condition	Ready to Deploy
80–89%	⚠️ Needs Attention	Schedule Maintenance
70–79%	🔧 Work Required	Partial Use or Repair
< 70%	❌ Retire	Remove from Active Duty

**🧠 Machine Learning Models**
We implemented and compared the following ML models:
1. Random Forest Classifier – Ensemble method that uses multiple decision trees.
2. Support Vector Machine (SVM) – Good for high-dimensional data with strong classification boundaries.

**✔️ Our models achieved up to 96% accuracy on the test sets.**

**📊 Data Description**
Each equipment dataset includes parameters such as:
- Type (Weapon / Jet / Vehicle)
- Battalion Area
- Temperature & Weather Conditions
- Usage Hours
- Failure Incidents
- Performance Metrics

**Datasets:**
- jets_data_updated.csv
- guns_data_with_environment.csv
- IEEE_DRDO_data.csv

**🖥️ Web Application**
We built a Flask-based dashboard with a clean, responsive frontend.

**Key Features:**
- Input Equipment ID to view current status
- Usage vs Performance visualizations
- Temperature & Environment analysis
- Light/Dark Mode Toggle
- Separate category folders for each equipment type

**How It Works (Workflow)**
1. Data Ingestion – Load .csv files into pandas DataFrames
2. Preprocessing – Handle nulls, convert categories, scale values
3. Model Training – Train Random Forest and SVM models
4. Model Evaluation – Accuracy, Confusion Matrix, Precision, Recall
5. Flask Integration – Wrap model in app.py for prediction
6. Visualization – Render plots via matplotlib/seaborn

**💡 Future Enhancements**
1. IoT Integration – Real-time sensor input from military assets
2. Live Dashboard – Continuous status updates from units
3. Federated Learning – Train across branches without sharing sensitive data
4. Multi-force Deployment – Extend to Army, Navy, and Air Force

**🧰 Tech Stack**
- Python, pandas, numpy, scikit-learn
- Flask
- HTML, CSS, JS
- MySQL (optional for data storage)
- Jupyter Notebook, VS Code

**🛠 Installation & Setup**
1. Install dependencies:
   pip install -r requirements.txt
   
3. Run the Flask App:
   python app.py

4. Open in browser:
   http://127.0.0.1:5000/

**👨‍💻 Contributors**
- Sukalp Jhingran
- Hardik Raj Kapoor
- Mentor: Dr. Tanupriya Choudhury

**📃 License**
This project is intended for academic demonstration purposes only. For external use, please contact the maintainers.
🔗 Stay Mission-Ready. Predict. Prevent. Perform.
