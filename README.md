# **Healthcare-Data-Analysis**

# Introduction
This dataset contains comprehensive information about patients, their admissions, and the healthcare services they received, making it valuable for various data analysis and modeling tasks in the healthcare domain. It includes details such as patient demographics, medical conditions, admission and discharge dates, attending doctors, healthcare facilities, insurance providers, billing amounts, room numbers, types of admissions, prescribed medications, and test results. Each column provides specific insights, ensuring a detailed and multifaceted understanding of patient care and healthcare service delivery.

# Data Description
Each column in this dataset provides detailed information about the patient, their admission, and the healthcare services received.  Below is a brief description of each column in the dataset:

- `Name`: The patient's name linked to the healthcare record.
- `Age`: The patient's age in years at the time of admission.
- `Gender`: The patient's gender, either "Male" or "Female."
- `Blood Type`: The patient's blood type, such as "A+," "O-," etc.
- `Medical Condition`: The primary diagnosis or medical condition of the patient, like "Diabetes," "Hypertension," "Asthma, etc.
- `Date of Admission`: The date when the patient was admitted to the healthcare facility.
- `Doctor`: The name of the doctor overseeing the patient's care during their admission.
- `Hospital`: The healthcare facility or hospital where the patient was admitted.
- `Insurance Provider`: The patient's insurance provider, including options like "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," and "Medicare."
- `Billing Amount`: The billed amount for the patient's healthcare services during their admission, represented as a floating-point number.
- `Room Number`: The room number where the patient stayed during their admission.
- `Admission Type`: The type of admission, which can be "Emergency," "Elective," or "Urgent," indicating the nature of the admission.
- `Discharge Date`: The date the patient was discharged from the healthcare facility, determined by the admission date and a randomly assigned realistic number of days.
- `Medication`: The medication prescribed or administered to the patient during their stay, such as "Aspirin," "Ibuprofen," "Penicillin," "Paracetamol," or "Lipitor."
- `Test Results`: The outcome of a medical test conducted during the patient's admission, which can be "Normal," "Abnormal," or "Inconclusive."


# Installation
To run this project, ensure you have Python installed. Follow these steps to set up the environment:

Clone the repository:
- "git clone https://github.com/AneleMaphalala/Healthcare-Data-Analysis.git"
- "cd Healthcare-Data-Analysis"

Create a virtual environment:
- "python -m venv env"
- "source env/bin/activate # On Windows, use env\Scripts\activate"


# Summary and Impact
**33% of admissions were classified as "Elective," indicating proactive healthcare planning and opportunities for more efficient resource allocation in hospitals.**
- `Proactive Healthcare Management`: Many patients are scheduling treatments or procedures in advance, which may point to better healthcare planning, especially for non-urgent or chronic conditions.
- `Resource Allocation`: Hospitals can allocate resources (e.g., staffing, facilities) more efficiently for elective procedures, as they are scheduled ahead of time.
- `Focus on Preventative Care`: Elective admissions may include surgeries or treatments for conditions that are caught early, potentially reducing emergency admissions in the long run.
- `Financial Predictability`: Elective admissions can provide more predictable revenue streams for healthcare facilities compared to emergency care, which is often less predictable.

**A- (34%) and A+(34%) blood types were the most common among patients, highlighting the need for hospitals to prioritize blood supplies and tailor resources for blood-related treatments and interventions.**
- `Preparedness for Blood Transfusions`: Hospitals may need to stock adequate supplies of A- and A+ blood types for transfusions and surgeries, ensuring they meet the demands of the most common blood types among patients.
- `Potential for Blood Donation Campaigns`: Targeting blood donation drives towards A- and A+ donors could help maintain sufficient reserves of these blood types, which may be in higher demand.
- `Healthcare Focus on Blood-related Conditions`: Patients with A- and A+ blood types might have unique health considerations, and healthcare providers could tailor treatments or interventions accordingly.

**Observed a high prevalence of chronic conditions like Arthritis (17%) and Diabetes (17%) indicating key areas for targeted health interventions.**
- These findings point to key areas for targeted health interventions, including specialized treatment plans and preventative care programs aimed at managing and reducing the long-term impact of these conditions.

**Patient demographics dashboard revealed an age distribution skewed towards patients aged 36-64, indicating a higher demand for age-specific medical services.**
This suggests an increasing need for healthcare resources focused on mid-life and pre-retirement populations, including routine screenings, lifestyle interventions, and specialized care for managing age-related health concerns.