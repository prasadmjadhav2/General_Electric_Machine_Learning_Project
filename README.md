![GE](https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/General_Electric_logo.svg/220px-General_Electric_logo.svg.png)

# GE Machine Learning Projects

Welcome to the repository showcasing my recent machine learning projects with **GE Aerospace**, **GE Vernova**, and **GE HealthCare**. These projects demonstrate the application of advanced machine learning techniques to solve real-world problems in manufacturing, clean energy, and healthcare domains.

---

![GE Aerospace](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/GE_Aerospace_logo.svg/512px-GE_Aerospace_logo.svg.png)

## 🚀 GE Aerospace: Driving Innovation in Manufacturing

### Problem Statement
Predict potential defects early in the production cycle to enhance quality control and reduce scrap rates.

### Dataset
- **Size**: 1 million rows, 22 features
- **Key Features**: Temperature, Pressure, Production Time, Operator Experience, Maintenance Flags, etc.

### Approach
1. **Data Cleaning & Preprocessing**:
   - Managed missing values and ensured data consistency.
   - Engineered features such as temperature deviation and pressure deviation.
2. **Model Selection**:
   - Used **XGBoost Classifier** for classification.
   - Achieved 90% accuracy in defect prediction.
3. **Imbalanced Data Handling**:
   - Applied **SMOTE** to balance classes, improving model robustness.
4. **Hyperparameter Tuning**:
   - Fine-tuned model parameters to optimize accuracy.
5. **Model Deployment**:
   - Exported the trained model for real-time predictions.

### Results
- **Accuracy**: 90%+
- **Precision/Recall**: Optimized for defect detection.
- **Impact**: Enhanced quality control and reduced production waste.

---

![GE Vernova](https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/GE_Vernova_logo.svg/512px-GE_Vernova_logo.svg.png?20240402203816)

## ⚡ GE Vernova: Advancing Clean Energy with AI

### Objective
Enhance energy production, optimize operational efficiency, and reduce costs across sectors such as Wind Power, Electrification, and Power Generation.

### Dataset
- **Size**: 100,000 records, 29 features
- **Key Features**: Energy production, carbon footprint, operational efficiency, maintenance costs, etc.

### Use Cases & Solutions
1. **Energy Production Prediction**:
   - Used **Gradient Boosting Regressor** with an RMSE of 2,885.
2. **Anomaly Detection**:
   - Leveraged **Isolation Forest** to detect 1,000 operational anomalies.
3. **Customer Satisfaction Modeling**:
   - Built a model to predict satisfaction scores using Gradient Boosting.
4. **Sector Clustering**:
   - Applied **KMeans clustering** for performance-based grouping.
5. **Time Series Forecasting**:
   - Used **ARIMA** to forecast revenue impact.

### Results
- Increased operational efficiency and reliability.
- Enhanced customer satisfaction through actionable insights.
- Reduced downtime and optimized maintenance scheduling.

---

![GE HealthCare](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/GE_HealthCare_logo_2023.png/800px-GE_HealthCare_logo_2023.png)

## 🩺 GE HealthCare: Transforming Medical Device Analytics with AI

### Objective
Apply AI techniques to enhance operational efficiency, predict pricing, and improve product performance for medical devices.

### Dataset
- **Size**: 10,000 records, 32 features
- **Key Features**: Device type, energy consumption, customer ratings, AI integration, regulatory compliance, etc.

### Use Cases & Achievements
1. **Unit Price Prediction**:
   - Trained a **Random Forest Regressor**, achieving:
     - **MAE**: $22,708.47
     - **RMSE**: $26,520.46
2. **Error Rate Prediction**:
   - Developed a **Gradient Boosting Regressor** with an R² score of 0.52.
   - Identified factors like maintenance frequency and software version influencing performance.
3. **Advanced Feature Engineering**:
   - Extracted specifications and optimized datasets with imputation and dimensionality reduction.
4. **Model Optimization**:
   - Fine-tuned models using **GridSearchCV** and **XGBoost**.
5. **Explainability**:
   - Used **SHAP** to interpret model predictions.

### Results
- **Enhanced Price Predictions**: Enabled data-driven pricing strategies.
- **Proactive Maintenance**: Predicted error rates to optimize device reliability.
- **Scalable Framework**: Delivered a robust solution for predictive analytics.

---

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: pandas, numpy, scikit-learn, XGBoost, SMOTE, SHAP, Gradient Boosting, ARIMA
- **Tools**: Jupyter Notebook, GridSearchCV

---

## Repository Structure
```
├── GE_Aerospace
│   ├── data
│   ├── notebooks
│   └── models
├── GE_Vernova
│   ├── data
│   ├── notebooks
│   └── models
├── GE_HealthCare
│   ├── data
│   ├── notebooks
│   └── models
└── README.md
```

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ge-ml-projects.git
   ```
2. Navigate to the specific project folder (e.g., `GE_Aerospace`).
3. Explore the Jupyter notebooks for code and detailed analysis.
4. Load datasets and run the models to replicate results.

---

## Contact
I’d love to connect and discuss these projects further! Feel free to reach out via:
- **LinkedIn**: [LinkedIn](https://linkedin.comin/prasadmjadhav2)
- **Email**: prasadmjadhav6161@gmail.com

---

## Acknowledgments
- Special thanks to **GE Aerospace**, **GE Vernova**, and **GE HealthCare** for the opportunity to work on these impactful projects.
- Thanks to the open-source community for the tools and libraries used.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

# Let’s innovate together! 🚀
