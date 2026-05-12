# CareBridge: An Intelligent Health Risk Assessment and Doctor Recommendation System

## Overview

CareBridge is an AI-powered healthcare assistant developed as part of the Artificial Intelligence & Machine Learning Lab project at Jaypee Institute of Information Technology.

The system analyzes user-input symptoms and predicts possible diseases using multiple machine learning and deep learning models. It also performs risk assessment, recommends medical departments, and provides disease-related information and precautions through a user-friendly web interface.

---

## Problem Statement

In today’s fast-paced world, individuals often ignore early symptoms or lack sufficient medical knowledge to interpret them accurately. This may lead to delayed diagnosis, worsening health conditions, and increased healthcare costs.

CareBridge addresses this problem by providing:

- Disease prediction based on symptoms
- Multiple probable disease outputs
- Confidence scores for predictions
- Severity-based risk analysis
- Medical department recommendation
- Real-time healthcare guidance

---

## Key Features

- Multi-model disease prediction system
- Top 3 disease predictions with confidence scores
- Severity score calculation
- Risk classification (Low, Medium, High)
- Department recommendation system
- Disease descriptions and precautions
- Real-time backend integration
- Interactive web interface
- Model comparison and evaluation
- Data visualization and analysis

---

## Technologies Used

### Programming & Backend
- Python
- Flask / FastAPI

### Libraries
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- TensorFlow / Keras

### Frontend
- HTML
- CSS
- JavaScript

### Data Handling
- JSON

---

## Datasets Used

- Symptom–Disease Dataset
- Symptom Severity Dataset
- Disease Description Dataset
- Disease Precaution Dataset

---

## Machine Learning Models Used

### Traditional Machine Learning
- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression
- Support Vector Machine (SVM – RBF Kernel)

### Deep Learning
- Artificial Neural Network (ANN – Keras)
- Convolutional Neural Network (CNN – LeNet)

### Unsupervised Learning
- K-Means Clustering
- PCA (Principal Component Analysis)

---

## Model Performance

| Model | Accuracy |
|------|------|
| ANN (Keras) | 99.39% |
| Logistic Regression | 99.29% |
| SVM (RBF) | 99.29% |
| Random Forest | 89.75% |
| CNN (LeNet) | 83.25% |
| Decision Tree | 75.84% |

---

## Final Model Selection

The Artificial Neural Network (ANN) was selected as the final model due to its highest accuracy and strong capability to capture complex non-linear relationships between symptoms and diseases.

---

## System Workflow

1. User enters symptoms through the web interface
2. Backend processes the input data
3. ML/DL models predict possible diseases
4. Risk severity is calculated
5. Appropriate medical department is recommended
6. Disease descriptions and precautions are displayed

---

## Outputs

- Dataset analysis
- Trained ML/DL models
- Accuracy comparison graphs
- Disease prediction results
- Risk assessment reports
- Interactive healthcare website

---

## Project Structure

```bash
CareBridge/
│
├── datasets/
├── models/
├── notebooks/
├── static/
├── templates/
├── app.py
├── index.html
├── requirements.txt
└── README.md
```

---

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/carebridge-healthcare-system.git
```

### Step 2: Move to Project Folder

```bash
cd carebridge-healthcare-system
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Open in Browser

```bash
http://127.0.0.1:5000
```

---

## Team Members

- Arolika Shanker 
- Kirpa Gupta 
- Shreyanshi Agarwal 
- Yogyata Bhatnagar 

---

## References

- Breiman, L. (2001). Random Forests. Machine Learning, 45, 5–32.
- Scikit-learn Documentation  
  https://scikit-learn.org/stable/

- SciPy Stats Documentation  
  https://docs.scipy.org/doc/scipy/reference/stats.html

- Disease Prediction and Medical Recommendation System  
  https://github.com/sohamvsonar/Disease-Prediction-and-Medical-Recommendation-System

- Kaggle Dataset  
  https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset

---

## Future Enhancements

- Chatbot-based healthcare assistant
- Voice-based symptom input
- Mobile application integration
- Cloud deployment
- Real-time appointment booking
- Advanced medical analytics

---

## License

This project is developed for academic and educational purposes.
