https://drive.google.com/file/d/13-Xl6SCDkPdcoBjuvcJKsLyfBSZom0jv/view?usp=drivesdk

📱 MobileFrappe - Mobile Phone Activity Classification

MobileFrappe is a machine learning-based web application that classifies mobile app usage into categories like Home, Work, or Unknown. 
It helps users gain insights into their mobile usage behavior and offers potential applications in productivity tracking, workplace monitoring, and parental control.

🔍 What the Project Does:
- Analyzes mobile app usage data such as app name, usage time, and usage frequency.
- Classifies user activity into three meaningful categories: Home, Work, or Unknown.
- Trains and evaluates several machine learning models to identify the best-performing algorithm for accurate classification.
- Deploys the final model in a user-friendly Flask web interface to provide real-time predictions.

- Supports:
  • 📊 Productivity Monitoring – Track which apps are contributing to work or distractions.
  • 🧑‍💼 Workplace Oversight – Employers can use this to understand usage trends on company devices.
  • 👨‍👩‍👧‍👦 Parental Control – Parents can analyze their child’s app usage to determine if it aligns with learning or entertainment during study hours.

🌟 Key Features:
- Multi-class classification: Home, Work, Unknown
- Experiments with a variety of classification algorithms
- Finalized best-performing model based on accuracy and F1-score
- Deployed as a web app using Flask
- Metrics tracked: Accuracy, Precision, Recall, F1-Score

🧠 Models Used:
The following classification models were implemented and evaluated:
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- AdaBoost Classifier
- Bagging Classifier ✅ (Finalized Model)

Final Model: BaggingClassifier
After evaluating multiple models using metrics like accuracy, precision, recall, and F1-score — BaggingClassifier was selected as the final model due to its superior and balanced performance.
The trained model is saved as model.pkl using joblib for deployment.

🚀 How to Run the Project:
1. Clone the Repository:
   git clone https://github.com/your-username/mobilefrappe.git
   cd mobilefrappe

2. (Optional) Create Virtual Environment:
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Dependencies:
   pip install -r requirements.txt

4. Run the Flask App:
   python app.py

5. View in Browser:
   http://localhost:5000
