# Global-Healthcare-Analysis
## Page 1
![Page 1](https://github.com/user-attachments/assets/9b23a6bd-f290-467b-aa2e-bab3e04b3509)

## Page 2
![Page 2](https://github.com/user-attachments/assets/caf4a840-1f22-4b9a-a81c-7a072c3adb95)

## Business Problem
* Every year, millions of people across the globe are affected by preventable or treatable diseases — but not everyone has the same access    to healthcare, treatment, or recovery. Some countries have strong healthcare systems but still struggle with recovery rates. Others have    low access to care but surprisingly high resilience. 
* There’s clearly a gap — but where exactly is it, and what’s driving it?
* This project explores global health data to uncover patterns and disparities in disease prevalence, healthcare access, treatment            availability, recovery rates, and the impact of socio-economic factors like income, education, and urbanization.

## Business Questions
**1. Which diseases are affecting the most people, and where?**

**2. Is higher healthcare access actually leading to better recovery?**

**3. Which countries are spending more on treatment, and is it worth it?**

**4. How much does income or education impact health outcomes?**

---

## Insights
1. **Narrow Recovery Rate Range Across Genders:** Recovery rates range between 74.29 and 74.72, indicating minimal variation and           possibly standardized treatment protocols or uniform reporting.
2. **Gender-Specific Disease Recovery Trends:**
   - **Female:** Highest in Hypertension, Measles, Dengue.
   - **Male:** Highest in Parkinson’s, Influenza, Rabies.
   - **Other Gender:** Leads in Cholera, HIV/AIDS, Malaria.
3. **Diseases with Highest Gender-Based Variation**
   Notable recovery rate differences seen in:
   - Parkinson’s Disease (Range: 0.31)
   - Zika (Range: 0.27)
   - Asthma (Range: 0.28)
4. **Diseases with Uniform Recovery Rates Across Genders:** COVID-19, Rabies, Tuberculosis show minimal variation (~0.1), likely due to    global protocols or minimal gender influence on recovery.
5. **Diseases with Consistently Low Recovery Rates:** Polio has the lowest rate across all genders, possibly due to long-term              complications or delayed treatment and Ebola particularly low for males, suggesting gender-linked vulnerability or differing access      to care.
6. **Overall Gender Trends**
   - Males show better recovery in neurological diseases.
   - Females show better recovery in chronic diseases like Hypertension and Cancer.
   - Other gender fares better in infectious/tropical diseases.
  
## Recommendations
1. Implement Gender-Sensitive Healthcare Strategies
2. Customize treatment protocols for diseases showing gender-based disparities (e.g., Parkinson’s, Zika, Asthma).
3. Target Public Health Campaigns by Gender & Disease Type
4. Focus education and outreach on diseases where one gender shows lower recovery—e.g., Polio in females, Ebola in males.
5. Investigate biological, social, and systemic factors driving recovery rate differences among genders.
6. Ensure Equitable Healthcare Access
7. Address potential inequities in treatment availability, affordability, or cultural barriers, especially for non-binary and               marginalized genders.
---
## Dataset
[https://github.com/Sujay93/Global-Healthcare-Analysis/blob/main/Cleaned_Global_Health_Statistics.csv]

## Data cleaning

* Imported the dataset using Python libraries to prepare for analysis.
* Identified and removed duplicates to maintain data accuracy.
* Handled missing values through appropriate replacement strategies to ensure completeness.
* Eliminated irrelevant columns not aligned with the analysis objectives.
* Validated and corrected data types for consistency and analytical accuracy.
* Standardized formatting to enhance data usability for analysis
* Exported the cleaned data set to PowerBI for data visualization and analysis.

## Data Visualization and Analysis
1. **Healthcare Access vs Recovery rate by country**
![Healthcare access vs Recovery rate](https://github.com/user-attachments/assets/d7180332-4ddc-451c-aa58-edfba2f78bb3)

* **Stable Healthcare Access, Variable Recovery Rates:** Most countries have consistent healthcare access scores (~74.9–75.2), but        recovery rates vary more significantly, indicating differences in healthcare effectiveness.
* **Outliers:** Countries like Indonesia, Brazil, and Argentina show lower recovery rates despite comparable or high healthcare            access, suggesting possible inefficiencies or external challenges affecting outcomes.
* **Efficient Performers:** Germany, South Korea, and Italy exhibit higher recovery rates than expected, pointing to effective use         of healthcare infrastructure.
* **Balanced Performers:** Nations like USA, Canada, Russia, China, and Australia maintain close alignment between healthcare access and   recovery rate, reflecting consistent healthcare performance.

2. **Total population affected by disease category**
![Total population affected by disease](https://github.com/user-attachments/assets/a57dc99c-59fa-4af6-bc84-3ab0e3956d59)

* Metabolic, Neurological, and Parasitic diseases are the top three contributors to global disease burden, each affecting over 45.6        billion people cumulatively.
* Autoimmune, Genetic, and Respiratory diseases form the mid-impact tier, showing slightly lower but still substantial population          effects.
* Chronic and Bacterial diseases appear least impactful in comparison, though their burden remains globally significant.
* The small variation in affected population across categories may indicate a highly scaled or aggregated dataset, suggesting the need     for normalized insights.

3. **Average cost based on Treatment type**
![Avg cost based on Treatment type](https://github.com/user-attachments/assets/77ffc45c-9981-45af-9b93-df97d48f16b6)

* Average treatment costs are remarkably uniform, ranging from 24.971K to 25.044K — a marginal difference of just 0.3%, suggesting         standardized pricing or resource allocation across treatment types.
* Medication emerges as the costliest treatment type, followed closely by therapy and surgery, while vaccination is the least expensive,   likely due to its one-time nature versus prolonged medication or therapy regimens.
* The narrow cost range may indicate aggregated or homogenized data, where deeper segmentation (by region, age, or insurance) could        reveal more meaningful variations.
* Visual cues like the color gradient effectively highlight minor cost differences, reinforcing the chart’s message despite minimal        variation in bar height.

4. **Average Mortality and Recovery rate**
![Avg Mortality and Recovery rate](https://github.com/user-attachments/assets/e223df08-c068-456e-a887-eae4da0b7956)

* Mortality rate has remained stable at around 5.0–5.1 over the two decades, indicating consistent healthcare outcomes in terms of         fatality prevention.
* Recovery rate shows noticeable year-to-year volatility, ranging between 74.38 and 74.65, suggesting the influence of disease             variation, healthcare system performance, and global health events.
* Significant recovery rate patterns include:
  - 2015 peak (74.647) – possibly due to advancements in treatment or low-severity diseases that year.
  - 2020 dip (74.384) – correlates with the COVID-19 pandemic's global impact.
  - 2021 rebound and 2023 slight decline – reflect pandemic recovery phases and possible emergence of new health challenges.
* The contrast between stable mortality and fluctuating recovery rates may indicate that while healthcare systems are preventing deaths    effectively, recovery outcomes still vary depending on yearly challenges and preparedness.

5. **Average Recovery rate by Disease and Gender**
![Avg recovery rate by disease and gender](https://github.com/user-attachments/assets/bb67b316-341b-4dda-baf2-e821bebef334)

* Recovery rates are tightly clustered across all genders (74.29 to 74.72), indicating standardized treatment outcomes and minimal         disparity.
* Gender-wise highlights:
  - Females recover best from Hypertension, Measles, and Dengue.
  - Males show highest recovery in Parkinson’s, Influenza, and Rabies.
  - Other gender leads in Cholera, HIV/AIDS, and Malaria recovery.
* Polio consistently has the lowest recovery rate for all genders, while COVID-19, Rabies, and Tuberculosis show minimal gender-based      variation (~0.1%), suggesting uniform global treatment standards.
* Notable gender-based variability exists in diseases like Parkinson’s, Cholera, and Zika, pointing to possible differences in treatment   response, exposure, or healthcare access.
* Gender-sensitive healthcare strategies could improve outcomes where disparities exist

## Conclusion
* This analysis addressed the key questions related to recovery rate patterns across diseases and genders. It revealed that while          overall recovery rates remain narrowly clustered, subtle yet important gender-specific trends exist.
* Certain diseases show marked variability in recovery outcomes, indicating the influence of biological, social, or healthcare access      factors.
* Conversely, the uniformity in some diseases points to effective global treatment protocols. These findings validate that gender and      disease type do play a role in healthcare outcomes, supporting the need for targeted strategies and deeper exploration to drive          equitable and efficient treatment plans.






