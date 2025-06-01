# Glycemic Control Prediction

This project predicts glycemic control (diabetes outcome) using a machine learning model trained on the PIMA Indian Diabetes dataset. The solution is deployed as a web application using Flask, allowing users to input medical parameters and get real-time predictions.

## 🔍 Project Overview

Glycemic control prediction can help in early identification of individuals at risk of diabetes. This project uses a Support Vector Machine (SVM) model for classification, wrapped in a simple user interface for real-world usability.

---

## 📂 Folder Structure

Glycemic_Control_Prediction/

│

├── SVM_MODEL.ipynb # Jupyter Notebook for model training

├── deployment.py # Flask backend deployment file

├── diabetes.csv # Dataset used for model training

├── diabetes-prediction-rfc-model.pkl # Saved model file (Pickle format)
│

├── templates/ # HTML files for frontend

│ ├── index.html

│ └── hospital.html

│

├── static/ # Static files (CSS, JS)

│ ├── style.css

│ └── script.js

│

├── images/ # Result visuals

│ ├── p1.png

│ ├── s1.png

│ └── ...

│

└── README.md # Project documentation



---

## 📊 Dataset

- **Source**: [Kaggle – PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Rows**: 768
- **Features**: 8 medical parameters + 1 target variable (Outcome)
- **Label**: `Outcome` (0: Non-Diabetic, 1: Diabetic)

---

## 🧠 Model Used

- **Algorithm**: Support Vector Machine (SVM)
- **Library**: `sklearn.svm.SVC`
- **Preprocessing**: StandardScaler for feature normalization
- **Evaluation Metric**: Accuracy Score
- **Model Storage**: `pickle` serialization

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/vaishu0803/Glycemic_Control_Prediction.git
cd Glycemic_Control_Prediction
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the App
bash
Copy
Edit
python deployment.py
Then go to http://localhost:5000 in your browser.



✅ Requirements
Create a file named requirements.txt with:



flask
pandas
numpy
scikit-learn
pickle-mixin
🙋‍♀️ Author
Vaishnavi Vaklapudi
Feel free to explore other projects on GitHub @vaishu0803

📜 License
This project is licensed under the MIT License.


---

Let me know if you want me to:
- Auto-generate `requirements.txt`
- Help add screenshots
- Push this to your GitHub as a commit (if you connect a GitHub token)
