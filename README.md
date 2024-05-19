# WiDS Datathon 2024 Challenge #2
## Dataset Description
The WiDS Datathon 2024 centers on predicting a patient's Metastatic Diagnosis Period using a dataset of around 19,000 records, divided into training and test sets.
Each record represents a patient and includes characteristics such as age, race, BMI, and zip code; diagnosis and treatment information related to breast and metastatic cancer.
geo-demographic data like income, education, rent, race, and poverty; and climate data linking health outcomes to external conditions.
The task involves utilizing these variables to predict the Metastatic Diagnosis Period in the test dataset. Participants are expected to handle messy data appropriately, reflecting real-world data scenarios.

- 1) The training dataset train.csv where the observed values of the outcome [Metastatic Diagnosis Period] for each row is provided.

- 2) The test dataset test.csv where we withhold the observed values of the outcome for each row

### Target
metastatic_diagnosis_period: This refers to the number of days from the initial breast cancer diagnosis to the diagnosis of metastatic cancer, indicating the progression of breast cancer to a metastatic state.

### Columns & rows
- The Training dataset consists of 13173 rows and 152 columns
- The Test dataset consists of 5646 rows and 151 columns
