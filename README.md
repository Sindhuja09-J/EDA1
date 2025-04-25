# EDA1
❤️ Heart Disease Dataset - Exploratory Data Analysis (EDA) This repository presents an exploratory data analysis on a heart disease dataset using Python. The objective is to extract insights, detect trends, and visualize relationships among medical attributes that may contribute to heart disease.

🧠 Project Objectives Understand the structure and key patterns in the dataset

Identify correlations between variables such as age, cholesterol, and heart disease presence

Visualize distributions and relationships using statistical plots

Provide a clean and organized foundation for future predictive modeling

📂 Dataset Description The dataset, commonly known as the Heart Disease UCI Dataset, contains health-related data of patients, with a target column indicating the presence (1) or absence (0) of heart disease.

Key Columns Used: age: Age of the patient sex: Gender (1 = male, 0 = female) cp: Chest pain type (categorical: 0 to 3) trestbps: Resting blood pressure chol: Serum cholesterol in mg/dl fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) restecg: Resting electrocardiographic results thalach: Maximum heart rate achieved exang: Exercise-induced angina (1 = yes; 0 = no) target: Diagnosis of heart disease (1 = disease present, 0 = absent)

🔍 EDA Steps Performed

Initial Inspection Displayed first few rows with .head() Checked dataset info (.info()) and null values Computed descriptive statistics with .describe()

Visual Exploration The analysis includes various plots to visually explore the relationships between features:

Age Distribution: Histogram showing the age spread across the dataset Target Count Plot: Bar chart showing the proportion of patients with and without heart disease Sex vs Target: Bar plot comparing gender distribution across heart disease outcomes Age vs Cholesterol Scatter Plot: Used to assess relationships between age and cholesterol Chest Pain Type (cp) vs Target: Count plot showing frequency of different chest pain types across heart disease classes Correlation Heatmap: A heatmap to show linear relationships among variables

📊 Visual Outputs All charts and plots are generated using Matplotlib and Seaborn. These visuals help uncover trends such as:

Higher chest pain types (cp=3) more often linked with heart disease

Males appearing more frequently in heart disease-positive cases

Cholesterol and max heart rate variations across age groups

🛠️ Tools & Libraries This project uses the following Python libraries:

pandas – for data handling and inspection

matplotlib – for static plots

seaborn – for aesthetically appealing statistical plots

numpy – for numerical computations (optional but recommended)

📌 Results & Insights The dataset exhibits noticeable patterns in age, chest pain type, and sex with respect to heart disease occurrence.

Several features like cholesterol and max heart rate require further investigation for deeper predictive insights.

The EDA sets a strong foundation for building classification models for heart disease prediction.
