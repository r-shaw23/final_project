# final_project
**Overview:**
According to the CDC, someone in the United States experiences a stroke every 40 seconds. In response, we conducted an in-depth analysis of a dataset to identify key contributors of strokes. Utlizing machine learning algorithms, we aimed to predict the likelihood of a stroke based on various patient factors.


**Dataset Details:**
Our dataset contains 5110 patient entries with the following variables:
id: unique identifier (patient)
gender: "Male", "Female" or "Other"
age: age of the patient
hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
ever_married: "No" or "Yes"
work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed" 
Residence_type: "Rural" or "Urban"
avg_glucose_level: average glucose level in blood
bmi: body mass index
smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
*"Unknown" in smoking_status means that the information is unavailable for this patient
stroke: 1 if the patient had a stroke or 0 if not

**Machine Learning Approach:**
Our objective was to predict stroke likelihood using all dataset variables. We utilized three machine learning algorithms:
•	Random Forest Classifier
•	Logistic Regression
•	Neural Networking
Key Insights:
•	Value Features: BMI, Age, Glucose level
•	Binary Features: Ever-married status, Hypertension, Heart disease
Some binary features required conversion from strings to numerical values for compatibility.
•	Despite scaling due to limited stroke incidents (200), accuracy increased by only 0.04%, showing minimal impact.
•	Logistic Regression demonstrated the highest accuracy at 95%, establishing it as a reliable stroke prediction algorithm for this dataset.
•	PCA showed age and glucose level as primary contributors to stroke incidents.


**Expectations vs. Findings:**
Contrary to prior assumptions based on external sources (e.g ncbi bmi data and mayoclinic), our dataset highlights different insights.


**Key Drivers:**
Machine learning results and Tableau visualizations suggest age, glucose level, and marital status as significant drivers for strokes.
Focus on Smoking:
Our analysis allocated considerable attention to smoking due to its widely recognized health risks. One source outlines the financial impact, noting insurers can charge smokers up to 50% more under the Affordable Care Act (also known as Tobacco Rating).

**Summary:**
In conclusion, our analysis emphasizes the importance of large, diverse datasets. While we present findings grounded in the provided data, it prompts questions about the sufficiency and representativeness of the dataset in revealing the complete truth about stroke risks. 


**Tableau Site**
https://public.tableau.com/app/profile/joseph.martinez2625/viz/ExploringHealthDynamicsInsightsintoFactorsInfluencingStrokeIncidenceandHealthcareCosts/Story7?publish=yes

**Sources**
https://parinsurance.com/how-smoking-affects-your-health-insurance-premiums/#:~:text=Tobacco%20Rating,to%2050%25%20more%20for%20premiums.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10005195/#:~:text=In%20this%20large%20population%2Dbased,rather%20than%20later%20in%20life
https://www.mayoclinic.org/diseases-conditions/stroke/symptoms-causes/syc-20350113
https://www.cdc.gov/stroke/facts.htm
