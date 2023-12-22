# Project_02
[Link to instructions](https://github.com/jantzla/Project_02/blob/main/Instructions.md)

# Dietary Recommendations for Depression: Insights from NHANES 2007-2020

# Overview
This project investigates the link between dietary habits and mental health using data from the CDC's National Health and Nutrition Examination Survey (NHANES) between 2007 and 2020. It examines differences in daily nutrient intake between adults with and without depression, exploring dietary implications for depression management. The analysis provides insights into potential nutritional strategies for improving mental well-being.

# Data Source
The analysis is based on data from the National Health and Nutrition Examination Survey (NHANES) for the years 2007 to 2020. This data encompasses various dimensions curcial for the data analysis.

DEMOGRAPHICS DATA:
Gender and Age: Fundamental demographic variables to examine the impact of dietary habits on depression across different age groups and genders.

QUESTIONAIRE DATA:
This component of the data utilises data derived from actual questionnaires completed by NHANES participants, providing direct insights into their dietary habits and mental health status.

1. Nutrition Intake Per Day: Participants were asked to recall and report their food and beverage intake over the last 24 hours. This detailed account includes the quantity and type of food consumed, allowing for an accurate calculation of the nutrient composition. The dataset subsequently displays the total intake of various nutrients, including both macro-nutrients (such as proteins, carbohydrates, fats) and micro-nutrients (such as vitamins and minerals).

2. Mental Health (Depression Screener): The dataset employs the PHQ-9 (Patient Health Questionnaire-9) as a measure of depression levels among participants. This well-established tool comprises nine questions that gauge the frequency and severity of depression symptoms, allowing for a nuanced understanding of the participants' mental health.

# Data Preparation + Analysis
RAW DATA
1. Identify all relevant datasets
2. Transform datasets (.xpt file) into .csv file
3. Identifying all relevant columns in each dataset
4. Creating one file for each questionaire for the whole duration (2007-2020)
5. Export as one big file fpr each questionaire (demo, diet, mental)

CLEAN DATA
1. Creating an excel file for explaination of the data ('Data_Decoder')
2. Assessing and dealing with NaNs and duplicates
3. Preparing columns for further analysis
4. Defining the timeline (2007-2020) as only in 2007 the PHQ-9 was introduced into the survey
5. Creating bins for the different degrees of depression (based in total score of PHQ-9)
6. Joining all three tables (demo, diet, mental) on 'patient_id'
7. Filtering only adults and dropping all incomplete rows
8. Exporting 'clean' dataset for analysis

DATA ANALYSIS
1. Assessing correlations between total_score (of PHQ-9) and gender, age, nutrients
2. Logistic regression (target = total_score)
3. Visualisations of data distribution and behaviour
4. Dealing with outliers
5. Statistical hypothesis testing (Mann-Whitney Test for non-normal distributed data, a = 0.05)
6. Export data as .xlsx file for Tableau
7. Create pivot table and export it as .csv file for Tabelau


# Tableau Dashboard
[Link to Tableau Dashboard](https://public.tableau.com/app/profile/laura.isabell.jantz/viz/Project_2_final_17025763063880/Dashboard?publish=yes)

# Summary of Results
The analysis has yielded several significant insights into the relationship between nutrition and depression among the participants:

1. Age and Depression: No significant differences in depression prevalence across different age groups were found. This suggests that age is not a strong predictor of depression as the condition affects people of all ages.

2. Gender Differences: Interestingly, the study indicates a higher prevalence of depression among women compared to men. This finding aligns with existing research highlighting gender disparities in mental health.

3. Nutrient Intake and Depression: All tested nutrients exhibited significant differences between depressed and non-depressed participants. This underscores the potential role of diet in mental health.

4. Caffeine and Sugar Consumption: A noticeably higher daily intake of caffeine and sugar was observed among depressed individuals. These dietary habits may contribute to mood fluctuations, potentially exacerbating symptoms of depression.

5. Diversity in Nutrient Intake: The data suggests that depressed individuals tend to have a less diverse nutrient intake compared to their non-depressed counterparts. This finding points to the importance of a varied diet for mental wellbeing.

# Future Directions
Building on these findings, there are several promising avenues for further research:

- Pre and Post-Pandemic Comparison: Investigating changes in depression rates and dietary patterns before and after the COVID-19 pandemic would provide valuable insights into the impact of global crises on mental health.

- Nutrient Intake and Other Health Conditions: Extending the analysis to explore the influence of nutrient intake on other health conditions, such as heart diseases, could reveal broader implications of dietary habits on physical and mental health.
