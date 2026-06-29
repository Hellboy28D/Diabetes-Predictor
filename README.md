# Diabetes-Predictor

🩺 Diabetes Predictor using Machine Learning

A Machine Learning project that predicts whether a person is likely to have diabetes based on medical attributes using Support Vector Machine (SVM) and Python ML libraries.

⸻

📌 Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help in timely diagnosis and treatment.

This project uses medical data and machine learning techniques to classify whether a person is diabetic or non-diabetic based on several health parameters.

The project follows a complete machine learning workflow:

* Data collection
* Data preprocessing
* Feature scaling
* Data splitting
* Model training
* Model evaluation
* Prediction system

⸻

🚀 Features

✅ Data preprocessing and analysis
✅ Feature scaling using StandardScaler
✅ Training and testing data split
✅ Support Vector Machine (SVM) model implementation
✅ Model accuracy evaluation
✅ Predictive system for new user input
✅ Structured project organization without Jupyter notebooks

⸻

📂 Project Structure

Diabetes-Predictor/
│
├── data/
│   └── diabetes.csv
│
├── models/
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── predict.py
│   └── utils.py
│
├── .gitignore
├── README.md
├── requirements.txt
└── venv/

⸻

🛠 Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Support Vector Machine (SVM)

⸻

⚙️ Installation

Clone the repository:

git clone https://github.com/Hellboy28D/Diabetes-Predictor.git

Move into the project directory:

cd Diabetes-Predictor

Create a virtual environment:

python -m venv venv

Activate virtual environment:

Mac/Linux:

source venv/bin/activate

Windows:

venv\Scripts\activate

Install required libraries:

pip install -r requirements.txt

⸻

▶️ Run Project

Run the training script:

python src/train.py

Run prediction:

python src/predict.py

⸻

📊 Machine Learning Workflow

1. Load diabetes dataset
2. Analyze and preprocess data
3. Separate features and target values
4. Scale numerical values
5. Split training and testing data
6. Train SVM model
7. Evaluate model performance
8. Predict diabetes status

⸻

📈 Example Output

Accuracy on Training Data: 0.78
Accuracy on Test Data: 0.77
The person is diabetic

⸻

🔮 Future Improvements

* Add Streamlit web interface
* Save trained model using Pickle
* Deploy project online
* Experiment with multiple ML algorithms:
    * Logistic Regression
    * Random Forest
    * XGBoost
    * Neural Networks
* Add Rust-based components for performance experiments and Python–Rust integration

⸻

👨‍💻 Author

Divakr (Hellboy28D)

GitHub:
https://github.com/Hellboy28D

⸻

⭐ If you like this project

Give the repository a star and feel free to contribute.
