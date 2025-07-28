# Project IBM Granite Using Google Colab
## Using Student Depression Dataset for Analysis

### Project Overview
This project analyzes a student depression dataset using IBM's Granite 3.3.8B AI model to identify key patterns and relationships between various factors affecting student mental health. The analysis categorizes data into four key domains:
- Demographic factors
- Academic factors 
- Lifestyle factors
- Risk factors

The AI model provides:
- Statistical correlation analysis
- Predictive insights
- Intervention recommendations
- Research suggestions

The project aims to:
- Identify patterns and differences in depression levels based on demographic factors such as age and gender.
- Analyze the impact of academic factors, such as academic pressure and CGPA, on depression levels.
- Assess the effects of lifestyle factors, including sleep duration and dietary habits, on students' mental health.
- Identify risk factors, such as suicidal thoughts and financial stress, that contribute to depression levels.
- Provide recommendations for more effective mental health interventions based on the analysis findings.

### Dataset [Student Depression]
### Student Depression Dataset.zip
Contains 11 variables measuring:
1. Age (Numerical)
2. Gender (Categorical)  
3. Academic Pressure (Scale 1-10)
4. CGPA (Numerical)
5. Study Satisfaction (Scale 1-5)
6. Sleep Duration (Hours)
7. Dietary Habits (Categorical)
8. Suicidal Thoughts (Binary)
9. Financial Stress (Scale 1-10)
10. Family Mental Health History (Binary)
11. Depression Score (PHQ-9 scale)

### Background
Mental health among students is an increasingly important issue worldwide, particularly among young people facing various academic and social pressures. Data indicates that depression rates among students are rising, which can negatively impact academic performance, social relationships, and overall quality of life. By understanding the contributing factors to depression, educational institutions can develop better-targeted support programs to help students cope with the challenges they face.

### Problem Statement
The specific problems to be addressed in this project include:
- High Depression Rates: Many students experience significant levels of depression, but the specific causes are often unidentified.
- Lack of Integrated Data: Existing data is often fragmented and does not provide a comprehensive view of the factors affecting students' mental health.
- Ineffective Interventions: Without a clear understanding of risk and protective factors, implemented interventions may not meet students' needs.
- Stigma and Awareness: Many students are reluctant to seek help due to the stigma associated with mental health, making it essential to understand the factors influencing their decisions.

### Approach
The approach to be used in this project includes the following steps:
- Data Collection: Gather a dataset that includes demographic, academic, lifestyle, and risk factor information from students. This dataset can be obtained through surveys or existing data sources.
- Data Cleaning and Preparation: Perform data cleaning to remove missing values, address duplicates, and ensure that all variables are correctly formatted for analysis.
-  Analysis: Conduct descriptive analysis to obtain an overview of the distribution of depression levels across different categories, such as age, gender, and other factors.
- Inferential Analysis: Use statistical techniques to test hypotheses about the relationships between different factors and depression levels. This may include regression analysis, t-tests, and analysis of variance (ANOVA).
- Modeling and Prediction: Build predictive models to identify the most influential factors affecting depression levels. These models can be used to predict the risk of depression among students based on existing variables.
- Recommendations and Reporting: Compile a report summarizing the analysis findings, providing recommendations for mental health interventions, and suggesting steps for further research.
- Dissemination of Results: Communicate the results to stakeholders, including educational institutions, mental health service providers, and students themselves, to raise awareness and support for mental health.

## Key Insights & Findings
### Demographic Factors
- **Age**: Students aged 19-21 show highest depression scores
- **Gender**: Female students report 23% higher depression scores than males

### Academic Factors
- Strong negative correlation (-0.65) between CGPA and depression
- Academic pressure accounts for 32% of depression score variance

### Lifestyle Factors
- Students with <6 hours sleep have 2.4x higher depression risk
- Poor dietary habits correlate with 18% higher depression scores

### Risk Factors
- Financial stress shows strongest correlation (r=0.71)
- Students with family mental health history are 3.1x more likely to report suicidal thoughts

## AI-Powered Analysis
IBM Granite 3.3.8B provides:
1. **Automated Categorization**:
   - Classifies raw data into meaningful domains without manual coding
   - Identifies non-linear relationships human analysts might miss
2. **Predictive Modeling**:
   - Achieves 89% accuracy in predicting high-risk students
   - Identifies interaction effects between factors
3. **Dynamic Insights**:
   - Updates findings as new data is added
   - Explains findings in natural language with statistical backing
4. **Intervention Recommendations**:
   - Priority 1: Sleep hygiene programs
   - Priority 2: Financial aid counseling
   - Priority 3: Academic support services

