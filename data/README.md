# CMPU 250 Codebook

| Variable Name | Variable Description |
|---------------|---------------------|
| Name | This column represents the first and last name of the patient associated with the healthcare record. |
| Age | The age of the patient at the time of admission, expressed in years. |
| Age Group | Buckets of different ages, created to help the algorithms utilize the age value as a predictor. 0-21, 22-40, 41-65, 65+. |
| Gender | Indicates the biological gender of the patient, either "Male" or "Female." |
| Blood Type | The blood type of the patient (O+/-, A+/-, B+/-, AB+/-). |
| Medical Condition | This column specifies the primary medical condition or diagnosis associated with the patient. |
| Date of Admission | The date on which the patient arrived at the hospital. |
| Hospital | Identifies the healthcare facility or hospital where the patient was admitted. |
| Insurance Provider | The insurance company who will be covering part of the final billing amount. |
| Billing Amount | The amount the patient is charged for their treatment and stay at the hospital. This is our outcome variable and is expressed as a floating-point number. |
| Admission Type | The severity/urgency of admission (Elective/Urgent/Emergency). |
| Admission Length | The duration of a patient's visit to the hospital, calculated using Date of Admission and Discharge Date. |
| Discharge Date | The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range. |
| Medication | Identifies a medication prescribed or administered to the patient during their admission. |
| Test Results | Describes the results of a medical test conducted during the patient's admission. Possible values include "Normal," "Abnormal," or "Inconclusive," indicating the outcome of the test. |
| Race | Indicates the ethnicity of the patient, possible values are "White," "African American," "Hispanic," "Asian," and "Multiracial." |


# Description of Datasets

`healthcare_dataset.csv` is the original dataset downloaded from Kaggle, with no modifications.

`cleaned_data.csv` contains all of the clearning and data preperation performed during the EDA portion of the project.

`full_data.csv` is the dataset with correlation injected into the relationship between predictors and the outcome variable. 

