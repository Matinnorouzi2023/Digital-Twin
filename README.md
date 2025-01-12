# **Project Title: Wind Turbine Data Analysis and Modeling with Machine Learning**

This project focuses on analyzing and modeling wind turbine data using machine learning techniques. It aims to predict power output based on environmental factors and optimize turbine performance through data-driven insights.

---

## **Key Features**

- **Data Analysis and Preprocessing:**  
  - Cleaned and processed wind turbine data by removing invalid values and standardizing features.  
  - Ensured data quality for accurate modeling and predictions.

- **Power Output Prediction Model:**  
  - Developed a linear regression model to predict active power output based on wind speed, wind direction, and power curve theory.  
  - Model optimization focused on providing realistic predictions and actionable insights.

- **Data Visualization:**  
  - Created scatter plots, correlation analysis, and heatmaps to explore patterns and relationships between wind turbine features.  
  - Visualized key insights for better understanding of turbine behavior.

- **Model Optimization and Evaluation:**  
  - Applied data standardization techniques to enhance model performance.  
  - Evaluated the model using R² and Mean Squared Error (MSE) for prediction accuracy.

---

# **Wind Turbine Power Prediction and Analysis Using Machine Learning**

This repository contains the implementation of a project focused on analyzing and predicting wind turbine power output using machine learning techniques. The project aims to improve understanding of wind turbine behavior and provide accurate predictions of power output based on sensor data.

---

## **Project Overview**

Wind energy is a vital component of sustainable energy solutions, and accurate prediction of wind turbine power output is critical for optimizing performance and efficiency. This project leverages real-world wind turbine sensor data to clean, visualize, and build predictive models, providing actionable insights into the relationship between environmental factors and power generation.

---

## **Features and Objectives**

- **Data Preprocessing**  
    - Handled missing values and filtered negative power values to ensure data quality.  
    - Standardized input features using `StandardScaler` to optimize regression model performance.

- **Data Visualization**  
    - Generated pair plots and heatmaps to explore correlations between variables, such as wind speed, direction, and active power output.

- **Model Development**  
    - Developed a linear regression model to predict turbine power output.  
    - Derived interpretable coefficients to understand the impact of each feature on the power output.

- **Model Evaluation**  
    - Assessed the model using key metrics:  
        - **R² (Coefficient of Determination):** Measures the model's explanatory power.  
        - **Mean Squared Error (MSE):** Evaluates the accuracy of predictions.

---

## **Key Results**

- Achieved interpretable predictions through a robust regression formula.  
- Identified key factors influencing power generation, providing valuable insights for wind energy optimization.

---

## **How to Use the Code**

1. **Clone the Repository:**  
    ```bash  
    git clone https://github.com/your-username/wind-turbine-power-prediction.git  
    cd wind-turbine-power-prediction  
    ```

2. **Install Dependencies:**  
    Install the required Python libraries using `requirements.txt`:  
    ```bash  
    pip install -r requirements.txt  
    ```

3. **Run the Code:**  
    - **Preprocess data:** Use the provided `data_preprocessing.py` script to clean and standardize the dataset.  
    - **Visualize data:** Use `data_visualization.py` to generate pair plots and heatmaps.  
    - **Train and evaluate the model:** Run `train_model.py` to build and test the regression model.

4. **Input Data:**  
    - The dataset should include features like wind speed, wind direction, and power output, with a CSV format as an example provided in the `data/` folder.

---

## **Technologies and Tools**

- **Programming Language:** Python  
- **Libraries Used:**  
    - Pandas, NumPy for data manipulation  
    - Matplotlib, Seaborn for visualization  
    - Scikit-learn for machine learning  

---

## **Future Scope**

- Extend the model to include advanced regression techniques (e.g., polynomial regression or neural networks).  
- Incorporate real-time data for dynamic prediction and monitoring.  
- Expand the project to analyze turbine efficiency under varying environmental conditions.

---
# **Wind Turbine Predictive Maintenance**

## **Overview of the Code Functionality**

1. **Libraries Imported**  
   - `numpy` and `pandas`: For numerical operations and data handling.  
   - `matplotlib.pyplot` and `seaborn`: For data visualization.  
   - `sklearn`: Indicates the intention to apply machine learning models (though not yet implemented).  

2. **Dataset Loading**  
   - Loads `predictive_maintenance.csv`, which contains maintenance data for machinery.  
   - Columns include device ID, failure occurrence, and sensor metrics (`metric1` to `metric9`).  

3. **Failure Detection**  
   - Iterates through the 'failure' column and prints the index and date for each failure (`failure == 1`).  
   - Identifies when and which devices experienced failures.  

---

## **Application in Wind Turbine Maintenance**

- **Identifying Failure Patterns:** Detects when turbines fail most frequently.  
- **Tracking Sensor Data:** Monitors vibration, temperature, and power output for signs of wear.  
- **Preventive Actions:** Enables timely maintenance by recognizing early failure signs.  

---

## **Model Recommendations for Predictive Maintenance**

### 1. **Gradient Boosting Models (e.g., XGBoost, LightGBM)**  
- **Accuracy:** High  
- **Error Rate:** Low  
- **Cost:** Moderate  
- **Why Best?** Handles complex patterns and imbalanced datasets effectively.  

### 2. **Random Forest Classifier**  
- **Accuracy:** Moderate to High  
- **Error Rate:** Moderate  
- **Cost:** Low to Moderate  
- **Why?** Easy to implement but may struggle with imbalanced data.  

### 3. **Logistic Regression**  
- **Accuracy:** Moderate  
- **Error Rate:** Higher for complex relationships  
- **Cost:** Low  
- **Why?** Simple and cost-effective but limited for complex problems.  

### 4. **Neural Networks (Deep Learning)**  
- **Accuracy:** Very High  
- **Error Rate:** Low  
- **Cost:** High  
- **Why?** Best for complex data but resource-intensive.  

---

## **Recommendation**

**Gradient Boosting Models (XGBoost)** are the most suitable for wind turbine maintenance due to their high accuracy, low error rate, and ability to manage complex, imbalanced datasets efficiently.

---

## **Future Scope**

- **Advanced Models:** Integrate advanced regression techniques (e.g., polynomial regression, neural networks).  
- **Real-Time Data:** Incorporate real-time data for dynamic prediction and monitoring.  
- **Environmental Impact:** Expand analysis to assess turbine efficiency under varying environmental conditions.  




## **Contributors**
Matin Norouzi

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
