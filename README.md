# NHANES_Inferential_2023
An epidemiologic inferential statistics project that explores the relationshIp between various variables in a National Health and Nutrition Examination Dataset (NHANES).

The analyses are conducted in Google Colab with each step documented.

# Steps

Data loading and preperation

Clean data before performing analyses

Categorical variables: check and document frequency counts to confirm data consistency

Continuous variables: check for placeholder values (7777, 9999) and handle these as appropriate (e.g., by removing or imputing)

Analysis and/or transformations

Visualizations (where relevant)

Brief summaries
Code, results, and any explanations are documented clearly within the notebook.
 

 # Questions and Analysis

 1. Marital status: Is there an association between marital status and education level?

Variables DMDMARTZ (marital status) and DMDEDUC2 (education level). Recode as specified.

2. Mean Sedentary behavior: Is there a difference in the mean sendentary behavior time between those who are married and those who are not married?

Variables: DMDMARTZ (marital status, recoded) and PAD680 (sedentary behaviour time, cleaned).

3. BP Sytolic: How does age and marital status affect systolic blood pressure?
   
Variables: DMDMARTZ (marital status recoded), (age) RIDAGEYR, and BPXOSY3 (systolic blood pressure).

4. Weight and Sedentary behavior: Is there a correlation between self-reported weight and minutes of sedentary behavior?

Variables: WHD020 (weight) cleaned, PAD680 (sedentary behaviour cleaned)

5. Optional analysis: Is there an association between age and minutes of sedentary behavior?

Variables: RIDAGEYR (age) and PAD680 (sedentary behavior cleaned)