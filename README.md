# Cardiac-Biomarker-and-Vital-Sign-Analytical-Report
## Introduction
Cardiovascular diseases (CVDs), particularly acute myocardial infarction (AMI), remain a leading global cause of morbidity and mortality, accounting for approximately 17.9 million deaths annually (WHO, 2023). The escalating prevalence of CVDs has been closely linked to modern lifestyle modifications, including sedentary behaviors and the widespread consumption of energy-dense, nutrient-poor diets high in processed carbohydrates and unhealthy fats. These dietary shifts, compounded by increasing urbanization and stress, have contributed to a surge in metabolic risk factors such as obesity, hypertension, and dyslipidemia—key precursors to atherosclerotic cardiovascular disease.

Cardiac biomarkers, including troponins, natriuretic peptides, and inflammatory markers, play a pivotal role in the early diagnosis, risk stratification, and prognostic assessment of AMI. Recent advances in high-sensitivity assays have further enhanced their predictive utility, enabling earlier intervention and improved clinical outcomes. However, gaps remain in translating biomarker research into effective public health strategies, particularly in preventive cardiology.

This study aims to (1) investigate the diagnostic and prognostic efficacy of established and emerging cardiac biomarkers in post-AMI patients, and (2) evaluate the role of biomarker-guided risk assessment in public health education. By correlating biomarker profiles with lifestyle factors, this research seeks to develop evidence-based recommendations for dietary modifications and preventive care. Ultimately, these findings may contribute to improved primary and secondary prevention strategies, reducing the global burden of coronary artery disease.

### Objective
The main objective of this research is to analyze cardiac biomarkers (e.g., troponin, CK-MB), vital signs (e.g., blood pressure, heart rate), and demographic factors (e.g., age, gender) in a population dataset with specific aim to:

i) Identify high-risk groups for heart attacks (e.g., males, specific age brackets like 51–69+).
ii) Evaluate biomarker patterns (e.g., elevated troponin, high CK-MB) and their correlation with heart attack outcomes.
iii) Assess lifestyle/disease linkages, such as diabetes/blood sugar levels, in predicting cardiac events.
iv) Develop predictive insights to stratify risk (e.g., "Troppin" high-risk category) and inform preventive strategies.

#### Methodology
##### Data Source
The data used for this research was obtained from a publicly available dataset hosted on the Kaggle repository. The dataset was originally collected at Zheen Hospital, located in Erbil, Iraq, over a five-month period from January 2019 to May 2019.
The dataset contains clinical and demographic records of individuals evaluated for heart attack risks. Key attributes include:
a) Age
b) Gender
c) Heart Rate
d) Systolic Blood Pressure
e) Diastolic Blood Pressure
f) Blood Sugar
g) CK-MB (Creatine Kinase-MB)
h) Troponin levels

The outcome variable is labeled as either positive or negative, indicating the presence or absence of a heart attack. 

#####  Data Transformation
To enhance easy readability and interpretaion of the dataset, data transformation was done on the numerical data.This transformation allowed for easier identification of risk patterns and associations among different health indicators. The transformation process is detailed as follows:

# Age Grouping:
Ages were grouped in intervals of 15 years ranging from 10 to 69 years, while individuals 69 years and above were categorized separately without further subdivision.

# Blood Sugar Level:
Based on medical guidelines, blood sugar values were categorized into four distinct groups:
Low: Below 70 mg/dL
Normal: 70–140 mg/dL
Prediabetes: 140–199 mg/dL
Diabetes: 200 mg/dL and above

# Heart Rate:
Using the World Health Organization (WHO) standard:
Low: Below 60 beats per minute (bpm)
Normal: 60–100 bpm
High: Above 100 bpm

# Diastolic Blood Pressure:
Low: Below 60 mmHg
Normal: 60–100 mmHg
High: Above 100 mmHg

# Systolic Blood Pressure:
Low: Below 90 mmHg
Normal: 90–119 mmHg
Elevated: 120–129 mmHg
High: 130 mmHg and above

# Troponin Levels:
Normal: Less than 0.04 ng/mL
Slightly Elevated: 0.04–0.10 ng/mL
Elevated: Above 0.10 ng/mL

# CK-MB (Creatine Kinase-MB):
Normal: 0–5 ng/mL
Mild Elevation: 5–10 ng/mL
Likely Elevated: 10–24 ng/mL
Elevated: 24 ng/mL and above

###### Potential Analysis 
a) Highest Risk by Age Group
b) Highest Risk by Gender
c) Highest Risk by Cardiac Biomarkers (Heart Rate,Diastolic BP, Systolic BP, Troponin Levels, CK-MB, Blood Sugar Level)

###### Insight
1. Age Group Risk Distribution:
- Highest risk: Ages 55-69 (357 cases).
- Followed by ages 40-54 (212 cases).
- Ages below 40 show much lower risk.
  
2. Gender Distribution:
- Males: 69.51% (563 cases)
- Females: 30.49% (247 cases)
- Males are more than twice as likely to suffer heart attacks.
  
3. Blood Sugar Levels:
- Most cases had normal sugar levels (517).
- Diabetics and prediabetics combined: 281 cases.
- Sugar imbalance remains a contributing factor.
  
4. Vital Sign Patterns:
- High systolic BP is common.
- Troponin is the most critical biomarker.
- CK-MB is relevant but less consistent.
  
## Recommendations:
1. Targeted Awareness and Screening:- Focus on males aged 55-69.
- Introduce routine screening, including troponin and BP.
  
2. Enhance Biomarker Monitoring:
- Make Troponin testing standard.
- Monitor CK-MB as a secondary marker.
  
3. Preventive Interventions for Diabetics and Prediabetics:
- Promote lifestyle changes in these groups.
  
4. Gender-Specific Programs:
- Create male-focused health initiatives and outreach.
  
5. Cross-Analysis with Other Risk Factors:
- Further study into lifestyle and other health factors is recommended
