# SpaceX Falcon 9 First Stage Landing Prediction
## End-to-End Machine Learning Pipeline

### Project Overview
This project predicts the successful landing of the SpaceX Falcon 9 first stage using machine learning algorithms. By predicting landing outcomes, we can estimate flight costs ( vs competitors\' +) and improve mission planning.

### Highlights & Results
* **Dataset**: 187 real SpaceX launches collected via the SpaceX API and web scraping.
* **Accuracy Achieved**: **94.74%** test accuracy using a Support Vector Machine (SVM) with class weight balancing.
* **Methodology**: Applied a 60/20/20 Train/Validation/Test split across 5 major classification models (Logistic Regression, Decision Trees, KNN, SVM, and Gradient Boosting).

### Repository Structure
1. _Data_Collection_and_Wrangling.ipynb\: API collection, web scraping, and data cleaning.
2. _EDA_and_SQL_Analysis.ipynb\: Exploratory data analysis using Pandas and SQL queries.
3. _Visualization_and_Mapping.ipynb\: Interactive maps (Folium) and launch site success analysis.
4. _ML_Model_Training_and_Evaluation.ipynb\: Data scaling, feature encoding, GridSearchCV, and model evaluation.
5. _Complete_Pipeline_Project.ipynb\: Executive summary of the entire end-to-end pipeline.

### Setup Instructions
`ash
pip install -r requirements.txt
`
