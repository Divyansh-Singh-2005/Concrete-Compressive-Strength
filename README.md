# Concrete-Compressive-Strength
# Concrete Compressive Strength Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Tool-Jupyter%20Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
Concrete is the most important material in civil engineering. The compressive strength of concrete is a highly non-linear function of age and ingredients. This project applies **Machine Learning regression techniques** to predict the compressive strength of concrete (in MPa) based on its composition and age.

The goal is to build a model that can accurately estimate strength without the need for expensive and time-consuming destructive testing.

## 📂 Dataset
The dataset used in this project is likely the [Concrete Compressive Strength Data Set](https://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength) from the UCI Machine Learning Repository.

**Shape:** 1030 instances, 9 attributes (8 features, 1 target).

### Features (Inputs)
| Feature Name | Unit | Description |
| :--- | :--- | :--- |
| **Cement** | kg/m³ | Amount of cement in the mixture |
| **Blast Furnace Slag** | kg/m³ | Waste product from iron smelting |
| **Fly Ash** | kg/m³ | Coal combustion product |
| **Water** | kg/m³ | Amount of water used |
| **Superplasticizer** | kg/m³ | Additive to reduce water content |
| **Coarse Aggregate** | kg/m³ | Larger stones/rocks |
| **Fine Aggregate** | kg/m³ | Sand particles |
| **Age** | Days | Curing time (1-365 days) |

### Target (Output)
* **Concrete Compressive Strength** (MPa - Megapascals)

## 🛠️ Technologies Used
* **Python** (Data Analysis & Modeling)
* **Pandas & NumPy** (Data Manipulation)
* **Matplotlib & Seaborn** (Data Visualization)
* **Scikit-Learn** (Machine Learning Models)
* **Jupyter Notebook** (IDE)

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Divyansh-Singh-2005/Concrete-Compressive-Strength.git](https://github.com/Divyansh-Singh-2005/Concrete-Compressive-Strength.git)
    cd Concrete-Compressive-Strength
    ```

2.  **Install dependencies:**
    *(If you don't have a requirements file, install the standard libraries)*
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3.  **Open the Notebook:**
    Navigate to the `Concrete Compressive Strength` folder and launch Jupyter:
    ```bash
    cd "Concrete Compressive Strength"
    jupyter notebook
    ```
    Open the `.ipynb` file to view the analysis and run the cells.

## 📊 Methodology
1.  **Data Preprocessing:** Checking for null values, handling duplicates, and scaling features (StandardScaler/MinMaxScaler).
2.  **Exploratory Data Analysis (EDA):** Correlation heatmaps, pair plots, and distribution analysis to understand feature relationships.
3.  **Model Building:** Training various regression models such as:
    * Linear Regression
    * Decision Tree Regressor
    * Random Forest Regressor
    * XGBoost / Gradient Boosting
4.  **Evaluation:** Comparing models using metrics like **RMSE** (Root Mean Squared Error) and **R² Score**.

## 📈 Results
*(You can update this section with your specific findings)*
* **Best Model:** [e.g., Random Forest Regressor]
* **R² Score:** [e.g., 0.92]
* **Conclusion:** The model successfully captures the non-linear relationship between the ingredients and the final strength, with Cement and Age being significant predictors.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Divyansh-Singh-2005/Concrete-Compressive-Strength/issues).

## 📜 License
This project is open-source and available under the MIT License.
