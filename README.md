# 🌱 Agrochemical Runoff Toxicity Prediction using Machine Learning & Deep Learning

## 📌 Project Overview

Agricultural activities involve extensive usage of fertilizers and pesticides, which often lead to **agrochemical runoff** during rainfall events. These pollutants enter nearby water bodies and cause severe environmental and ecological damage.

This project proposes an **AI-driven Agrochemical Runoff Toxicity Prediction System** capable of predicting contamination risk levels using environmental, soil, and climatic parameters.

The system applies multiple **Machine Learning, Deep Learning, and Federated Learning models** to accurately classify runoff toxicity into risk categories.

---

## 🎯 Objectives

* Predict agrochemical runoff toxicity levels.
* Analyze environmental risk caused by agricultural practices.
* Compare performance of classical ML and Deep Learning models.
* Reduce overfitting using realistic noise simulation.
* Provide scalable prediction suitable for IoT-based smart farming systems.

---

## 📊 Dataset Description

The dataset contains **100,000 synthetic agricultural samples** representing runoff conditions.

### Features Used

| Feature              | Description             |
| -------------------- | ----------------------- |
| Area_Acres           | Agricultural land area  |
| Rainfall_mm          | Rainfall intensity      |
| Rainfall_Duration_hr | Rainfall duration       |
| Soil_pH              | Soil acidity level      |
| Soil_Permeability    | Water absorption rate   |
| Slope_%              | Land slope              |
| Fertilizer_kg_acre   | Fertilizer usage        |
| Pesticide_kg_acre    | Pesticide usage         |
| Days_Since_Spray     | Time after spraying     |
| Soil_Moisture_%      | Soil moisture           |
| Runoff_Coeff         | Runoff coefficient      |
| Distance_to_Water_m  | Distance to water body  |
| Temp_C               | Temperature             |
| Humidity_%           | Humidity                |
| Flow_Velocity_mps    | Flow velocity           |
| Est_Chem_Load_mgL    | Estimated chemical load |
| Toxicity_Index       | Pollution index         |

### Target Variable

**Risk_Class**

* Safe
* Low
* Moderate
* High
* Critical

---

## 🧠 Implemented Models

The following models were implemented and evaluated:

### ✅ Machine Learning Models

* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* XGBoost Classifier

### ✅ Deep Learning Models

* Lightweight 1D CNN
* LSTM Network
* Temporal CNN
* ResNet-based Architecture

### ✅ Distributed Learning

* Federated Learning (FedAvg Algorithm)

---

## ⚙️ Methodology

1. Dataset preprocessing
2. Label encoding
3. Feature normalization
4. Noise injection for realistic modeling
5. Dataset split:

   * **Training — 80%**
   * **Validation — 10%**
   * **Testing — 10%**
6. Model training & optimization
7. Performance evaluation

---

## 📈 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve (Multi-class)
* Training vs Validation Accuracy
* Training vs Validation Loss

---

## 📊 Output Visualizations

✔ Training vs Validation Accuracy
✔ Training vs Validation Loss
✔ Validation Confusion Matrix
✔ Testing Confusion Matrix
✔ Metrics Comparison Bar Charts
✔ Multi-Class ROC Curve

---

## 🧪 Noise Injection (Important)

Synthetic datasets may cause unrealistically high accuracy.
Controlled Gaussian noise is added to simulate:

* Sensor measurement errors
* Environmental variability
* Agricultural uncertainty

This ensures realistic model generalization.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* XGBoost
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```
Agrochemical-Runoff-Prediction/
│
├── dataset/
│   └── agro_runoff_100000_samples.csv
│
├── models/
│   ├── CNN_Model.py
│   ├── LSTM_Model.py
│   ├── Decision_tree.py
│   ├── Random_forest.py
│   ├── SVM_Model.py
│   ├── ANN_Model.py
│   └── Federated_learning.py
│
├── results/
│   ├── confusion_matrix/
│   ├── roc_curves/
│   └── performance_plots/
│
├── README.md
└── requirements.txt
```

---

## ▶️ Installation & Execution

### Clone Repository

```bash
git clone https://github.com/your-username/agrochemical-runoff-prediction.git
cd agrochemical-runoff-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Model

```bash
python random_forest.py
```

---

## 📌 Applications

* Precision Agriculture
* Smart Irrigation Systems
* Environmental Monitoring
* IoT-based Farming
* Water Pollution Risk Assessment

---

## 🚀 Future Enhancements

* Real-time IoT sensor integration
* Satellite rainfall data integration
* Edge AI deployment
* Explainable AI (SHAP/LIME)
* Web dashboard visualization

---

## 📄 Research Contribution

This work demonstrates how **AI-based predictive analytics** can assist sustainable agriculture by forecasting agrochemical runoff risks and minimizing environmental damage.

---

## 👨‍💻 Author

**Velan D**
B.E Electronics and Communication Engineering

---

## ⭐ License

This project is intended for academic and research purposes.

---

⭐ *If you find this project useful, consider giving it a star!*
