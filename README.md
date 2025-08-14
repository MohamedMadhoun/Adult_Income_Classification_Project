### 📈 Adult Income Classification Project

**📜 Introduction**

This project aims to build a machine learning model that can predict whether an individual's income exceeds $50,000 per year, based on a set of demographic and professional characteristics. A dataset from the census database was used for this purpose.

**📁 Contents**

* `Adult_Income_Classification_Project_Clean_(1).ipynb`: This Jupyter Notebook file contains all the steps of the project, from data import and cleaning to analysis, model building, and evaluation.
* `README.md`: This file, which explains the project's contents and objectives.

**🚀 Project Phases**

1.  **Libraries & Data Import**: Imported necessary libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
2.  **Data Cleaning & EDA**:
    * Handled missing values.
    * Converted categorical variables to numerical values.
    * Performed statistical and descriptive analysis.
    * Conducted Data Visualization to understand data distribution and relationships.
3.  **Data Preparation**:
    * Split the data into training and testing sets.
    * Applied `OneHotEncoder` and `OrdinalEncoder` for categorical variables.
    * Used `StandardScaler` to standardize numerical variables.
    * Addressed data imbalance with the `SMOTE` technique to enhance model performance.
4.  **Model Building & Training**:
    * Used `RandomForestClassifier` as an initial model.
    * Trained a `Sequential` neural network model from `tensorflow.keras`.
5.  **Model Evaluation**:
    * Evaluated performance using `classification_report`, `confusion_matrix`, and `accuracy_score`.
    * Analyzed results to identify model strengths and weaknesses.

**⚙️ Requirements**

To run this project locally, you need to install the following libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* `imblearn`
* `tensorflow`

You can install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imblearn tensorflow

```
**📊 Results**

The final classification_report and confusion_matrix demonstrate the model's performance on the test dataset. The plot_history graph also illustrates how the model's accuracy and loss evolved during the training phases.

**👤 Author**

Mohammed Al-Madhoun
