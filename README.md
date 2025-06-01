
# 🩺 Diabetic Control Prediction using Machine Learning

This project predicts whether a patient has **good or poor glycemic (diabetic) control** using hospital data. It uses a **Support Vector Machine (SVM)** model to classify patient records based on various health features.

---

## 📁 Folder Structure

```
diabetes/
├── templates/                     # HTML templates for the frontend

├── deployment/                    # Flask or Streamlit deployment code

├── diabetes/                      # Main project logic and scripts

├── diabetes.xlsx                  # Dataset used for training and testing

├── SVM_MODEL.ipynb               # Jupyter notebook containing the SVM model

├── *.html, *.css, *.js           # Frontend pages, styling, and scripts

├── *.jpg, *.png                  # Output images, visualizations

├── mains/                        # Possibly contains main scripts or helpers

├── hospital*, no-diabetes*       # Output results or predictions
```

---

## 🧠 Model Used

- ✅ **Support Vector Machine (SVM)**: Trained and tested using patient data to predict glycemic control outcomes.
- The notebook `SVM_MODEL.ipynb` includes the full model training pipeline.

---

## 🗃️ Dataset

- **File**: `diabetes.xlsx`
- **Description**: Patient data including attributes such as glucose level, insulin use, diet patterns, and other clinical features.

---

## 🚀 How to Run

1. Set up your Python environment and required libraries.
2. Run the Flask app from the `deployment` folder using:
   ```bash
   python app.py
   ```
3. Upload patient data via the interface or enter values manually to receive predictions.

---

## 📊  images

- `p1` to `p6`, `s1` to `s3`, `dt1`, `dt2`, `dt3`: These are image files are used in building the website.
- `hospital.html`, `index.html`: Interactive web pages to display results.

---

## ✅ File Saving Instructions (for team members)

Please save all files following the structure shown above. Keep related files (e.g., images, notebooks, HTML) clearly named and organized for smooth collaboration.

---

## 👩‍💻 Author
Vaishnavi Yenumula
This project was developed for healthcare analytics using machine learning models.

