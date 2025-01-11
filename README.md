

---

# Analyzing Driver Behavior and Crash Factors Using Machine Learning

🚗 **A Data Science Project to Explore Crash Data and Build Predictive Models for Traffic Safety.** 

## 🌟 **Project Overview**
This project explores and analyzes crash reporting data to identify factors influencing accidents, predict driver fault, and uncover insights to improve traffic safety. Machine learning models are applied to classify driver fault and determine predictors of injury severity.

### 🎯 **Key Research Questions**
1. What are the most common weather conditions reported during crashes, and how do they vary across collision types?
2. How does driver distraction correlate with the extent of vehicle damage?
3. Can a predictive model classify whether a driver is at fault based on road, weather, and behavior variables?
4. What factors are the most significant predictors of crash injury severity using gradient boosting?

---

## 📊 **Dataset**
- **Source**: [Crash Reporting Drivers Data](https://catalog.data.gov/dataset/crash-reporting-drivers-data)
- **Description**: 184,521 observations with 39 variables, covering driver behavior, road conditions, weather, and crash severity.
- **License**: Data is public and obtained via [Data.gov](https://data.gov).

---

## 🔍 **Methods**
### Tools
- **Python**: For analysis and modeling.
- **Libraries**: 
  - `pandas` & `numpy` for data handling.
  - `matplotlib` & `seaborn` for visualization.
  - `scikit-learn` & `XGBoost` for machine learning.

### Techniques
- **Data Cleaning**: Handling missing values and duplicates.
- **EDA**: Analyzing relationships between variables (e.g., weather and collision types).
- **Machine Learning**: 
  - **Fault Classification**: Using XGBoost to predict driver fault.
  - **Feature Importance**: Gradient boosting to identify significant predictors of crash injury severity.

---

## 📈 **Key Results**
1. **Weather Conditions**: Clear weather accounts for most crashes, with rear-end collisions being the most frequent.
2. **Driver Distraction**: Non-distracted drivers are involved in the majority of crashes, but distraction significantly impacts damage severity.
3. **Driver Fault Model**: Achieved 78% accuracy with the XGBoost classifier.
4. **Top Predictors of Injury Severity**:
   - Driver substance abuse
   - Vehicle damage extent
   - Collision type

---

## 🚀 **How to Run**
### Prerequisites
1. Install Python 3.x and `pip`.
2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Driver_Behavior_Crash_Factors_ML.git
   cd Driver_Behavior_Crash_Factors_ML
   ```
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Launch the Notebook
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the notebook file: `Crash_Reporting_Drivers_Data.ipynb`.

---

## 🛠 **Interactive Features**
- Filter insights by weather or crash type using widgets.
- Explore feature importance interactively with sliders.
- View confusion matrix and classification reports for the ML model.

---

## 📂 **Repository Structure**
```plaintext
Driver_Behavior_Crash_Factors_ML/
│
├── notebooks/
│   └── Crash_Reporting_Drivers_Data.ipynb  # Jupyter Notebook with analysis
├── data/
│   └── Link to dataset source
├── reports/
│   └── Report.pdf                          # Detailed analysis report
├── images/
│   └── charts/                             # Visualizations and graphs
└── README.md                               # Project documentation
```

---

## 💡 **Future Improvements**
- Enhance the predictive model using deep learning.
- Add real-time dashboards for traffic safety insights.
- Expand analysis to additional datasets for broader insights.

---

## 🤝 **Contributions**
Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, please open an issue to discuss.

---

## 📜 **References**
- Ellison, A. B., et al. (2015). *Driver behavior profiles for road safety analysis*.
- Santos, K., et al. (2022). *A literature review of machine learning algorithms for crash injury severity prediction*.
- [More references in the project report](reports/Report.pdf).

---
