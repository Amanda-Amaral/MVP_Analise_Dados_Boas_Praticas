# Diverse Impacts on COVID-19 Hospitalization Risk

🦠 Exploratory Data Analysis and Preprocessing — COVID-19

This project is part of the MVP (Minimum Viable Product) of the postgraduate program in Data Science, focused on exploratory data analysis (EDA) and data preprocessing related to vulnerability to COVID-19.

📌 Objective

To explore and prepare a static dataset containing population, environmental, demographic, and public health features in order to investigate hypotheses related to the estimated risk of hospitalization due to COVID-19.

📊 Dataset

The dataset used is the COVID-19 Unified Dataset (Static), provided by Johns Hopkins University.

Key variables analyzed:

Prevalence of diseases (obesity, diabetes, hypertension, etc.)

Air pollution (PM2.5, NO₂)

Access to healthcare services

Population indicators

Target variable: Risk_High (estimated hospitalization risk due to COVID-19)

🔍 Hypotheses Explored

Which pre-existing condition presents the highest risk factor for COVID-19 hospitalization?

Do environmental and urban climate quality affect the incidence of chronic respiratory diseases?

Does access to healthcare directly influence the estimated hospitalization risk?

🧪 Steps Performed

Dataset ingestion and cleaning

Handling missing values

Univariate and bivariate analysis (histograms, boxplots, heatmaps)

Data normalization using MinMaxScaler

Feature selection and interpretation based on correlation with the target variable

🛠️ Tools & Libraries

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Google Colab

Jupyter Notebook

📁 Project Structure
📦 covid19-risk-analysis
├── README.md                       # Project documentation
├── LICENSE  
├── requirements.txt                # Required dependencies
├── data/
│   └── COVID-19_Static.csv         # Dataset used
├── notebooks/
│   └── Data_Analysis_and_Best_Practices.ipynb  # Main notebook

👩‍💻 Author

Amanda Amaral
Postgraduate Student — Data Science & Analytics
