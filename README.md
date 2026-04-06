<div align="center">
  <h1>🚀 SpaceX Falcon 9 First Stage Landing Prediction</h1>
  <p><strong>End-to-End Machine Learning Analytics Pipeline</strong></p>
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--Learn-1.3+-orange.svg" alt="Scikit-Learn">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg" alt="Pandas">
</div>

---

## 📋 Project Overview
SpaceX advertises Falcon 9 rocket launches at **$62 million**, compared to competitors whose costs exceed **$165 million**. The primary reason for this massive cost saving is their ability to reuse the first stage. Therefore, accurately predicting whether the first stage will successfully land is crucial for determining the overall cost of a launch. 

This project encompasses a full data science life cycle to predict the landing outcome of the Falcon 9 first stage.

## 🎯 Key Highlights & Results
* **Dataset Size:** 187 real-world SpaceX launches.
* **Peak Accuracy:** **94.74%** Test Accuracy achieved using a Support Vector Machine (SVM).
* **Data Sources:** Direct data pipelining via the SpaceX API and web scraping from Wikipedia.
* **Methodology:** 60/20/20 Train/Validation/Test data split ensuring robust and unbiased model evaluation, utilizing class-weight balancing for minority classes (landing failures).

## 🗂️ Repository Structure

| File/Notebook | Description |
|---|---|
| 📓 [\1_Data_Collection_and_Wrangling.ipynb\](1_Data_Collection_and_Wrangling.ipynb) | Fetch data from the SpaceX API, scrape Wikipedia, and perform initial data cleaning. |
| 📓 [\2_EDA_and_SQL_Analysis.ipynb\](2_EDA_and_SQL_Analysis.ipynb) | Exploratory Data Analysis (EDA) utilizing Pandas and SQL queries to uncover initial trends. |
| 📓 [\3_Visualization_and_Mapping.ipynb\](3_Visualization_and_Mapping.ipynb) | Interactive maps built with Folium to analyze launch site success rates and payload trajectories. |
| 📓 [\4_ML_Model_Training_and_Evaluation.ipynb\](4_ML_Model_Training_and_Evaluation.ipynb) | Feature encoding, scaling, GridSearchCV hyperparameter tuning, and comparing 5 ML models. |
| 📓 [\5_Complete_Pipeline_Project.ipynb\](5_Complete_Pipeline_Project.ipynb) | An executive overview presenting the entire end-to-end pipeline and its conclusive findings. |
| 📄 \dataset_part_1_cleaned.csv\ | The meticulously cleaned and formatted dataset used for the ML iterations. |

## 📊 Models Evaluated
Models were trained and optimized via \GridSearchCV\ on cross-validated \cv=5\ subsets.

1. **Logistic Regression** (84.21% accuracy)
2. **K-Nearest Neighbors (KNN)** (84.21% accuracy)
3. **Decision Tree Classifier** (86.84% accuracy)
4. **Gradient Boosting** (86.84% accuracy)
5. **Support Vector Machine (SVM)** 🏆 (**94.74% accuracy**)

*Check out \model_evaluation.png\ for ROC curves and Confusion Matrices demonstrating the SVM's capability to predict failure outcomes accurately without overfitting.*

## ⚙️ Setup & Installation

To run this project locally on your machine:

1. **Clone the repository:**
   \\\ash
   git clone https://github.com/shamiquekhan/Falcon-Landing-Analytics-End-to-End-Machine-Learning-Pipeline.git
   cd Falcon-Landing-Analytics-End-to-End-Machine-Learning-Pipeline
   \\\

2. **Install the required dependencies:**
   \\\ash
   pip install -r requirements.txt
   \\\

3. **Launch Jupyter Notebook:**
   \\\ash
   jupyter notebook
   \\\
   *Navigate through the notebooks \1\ to \5\ in sequential order to re-run the complete pipeline.*

---
*Created as part of an end-to-end Artificial Intelligence and Machine Learning analytics project.*


## 📖 Documentation
For an in-depth breakdown of the project's data architecture, ML models, preprocessing strategy, metrics, and technical analysis, please see our detailed **[Comprehensive Documentation](DOCUMENTATION.md)**.ITS AN END TO END ML PIPELINE.
