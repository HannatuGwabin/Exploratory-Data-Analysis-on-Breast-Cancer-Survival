# Exploratory-Data-Analysis-on-Breast-Cancer-Survival


![BREAST CANCER IMAGE](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/22f73ec9-4a0e-466d-86af-8df32ea81e34)


## Resources

• Data Source: Kaggle

• Jupyter notebook

• Packages: Pandas, Numpy, Matplotlib, and Seaborn


## Overview

Breast cancer is a type of cancer that forms or develops in the cells of the breast. Breast cancer can occur in both men and women, but it's far more common in women.

The exact causes of breast cancer are not fully understood. However, several risk factors have been identified, including age, family history of breast cancer, specific genetic mutations (such as BRCA1 and BRCA2), hormonal factors (early menstruation, late menopause, hormone replacement therapy), obesity, alcohol consumption, and radiation exposure.

## Exploratory Data Analysis

Understanding breast cancer survival data's underlying patterns, correlations, and characteristics requires exploratory data analysis (EDA). EDA assists researchers and analysts in gaining an understanding of the variables influencing breast cancer survival rates by analyzing and visualizing the data. The following are some significant justifications for the significance of EDA in terms of breast cancer survival:

Understanding breast cancer survival data's underlying patterns, correlations, and characteristics requires exploratory data analysis (EDA). EDA assists researchers and analysts in gaining an understanding of the variables influencing breast cancer survival rates by analyzing and visualizing the data. The following are some significant justifications for the significance of EDA in terms of breast cancer survival: • Understanding the data: EDA enables researchers to familiarize themselves with the dataset, its structure, and the variables at play. It aids in finding outliers, missing numbers, and other potential data quality problems that could affect the study.

• Identification of variables: EDA makes finding pertinent variables affecting breast cancer survivorship possible. It facilitates the selection of analysis-relevant variables, such as age, tumor size, tumor grade, hormone receptor status, lymph node involvement, etc.

• Patterns and relationships: EDA aids in identifying patterns and relationships in the data. For instance, it can reveal relationships between several factors, such as the connection between tumor size and survival rate. Identifying potential risk factors or protective variables that might affect survival results is also aided by this.

• Data visualization is made possible by EDA using a variety of plots and charts. Histograms, scatter plots, and box plots are examples of visual representations that can be used to spot distributions, trends, and potential outliers. Visualizations enhance comprehension by researchers and stakeholders and make it easier to share findings.

• EDA helps with feature engineering, which entails generating new derived variables or modifying old ones. By examining the data, researchers can find significant interactions or combinations of variables that could improve predicted accuracy.

• Data-driven decision-making: EDA offers insights based on solid evidence that can aid decision-making. It aids in understanding how many factors affect breast cancer survival, identifies patient populations at high risk, and directs the creation of individualized treatment plans.

• Creation of hypotheses: EDA makes it easier to develop theories to test. Researchers might create research questions and more focused studies to confirm or investigate potential causal linkages by examining the data and looking for patterns.

Overall, EDA is crucial for understanding breast cancer survival data because it establishes the groundwork for additional statistical modeling, testing of hypotheses, and reaching meaningful conclusions. It enables researchers to make wise choices, unearth insightful information, and advance knowledge of breast cancer treatment and patient outcomes.

## Variables in the Dataset:

1) Patient_ID: ID of the patient

2) Age: The age of the patient

3) Gender: The gender of the patient

4) Protein1, Protein2, Protein3, and Protein4: Expression levels

5) Tumor_Stage: Breast cancer stage of the patient

6) Histology: Infiltrating Ductal Carcinoma, Infiltration Lobular Carcinoma, and Mucinous Carcinoma

7) ER status (Estrogen Receptor): Positive/Negative

8) PR statuS (Progesterone Receptor): Positive/Negative

9) HER2 status (Human Epidermal Growth Factor Receptor 2): Positive/Negative

10) Surgery_type: Lumpectomy, Simple Mastectomy, Modified Radical Mastectomy, Other

11) Date_of_Surgery: The date of Surgery

12) Date_of_Last_Visit: The date of the last visit of the patient

13) Patient_Status: Whether the patient is Alive or Dead
    

## Techniques used

✅ Import Libraries (Pandas, Numpy, Matplotlib, and Seaborn).

✅ Data Inspection (import Data, Statistical Analysis, Data Shape, Data Info, and Check for missing Values).

✅ Data Cleaning (Drop Unnecessary Column, Drop Duplicates, Used Forwardfill to fill the missing values, and Change 'Age' Column from Float to Integer ).

✅ EDA (Univariate, Bivariate, Multivariate Analysis).


## Exploratory Data Analysis (EDA)

### UNIVARIATE ANALYSIS

#### -What is the survival rate?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/044636fb-0fc9-42bb-8732-aa5347d2739c)


Observation: We can see 78.6% of breast cancer patients are still alive while 21.4% are dead. This could be as a result of early detection, advanced treatment, or individual factors such as age and overall health.

Several factors might contribute to these survival disparities, including differences in tumor characteristics, hormone receptor status, treatment responses, and healthcare-seeking behaviors between women and men. Further research and analysis are necessary to understand these differences' underlying reasons and determine if they hold true in larger, more diverse populations.

​

#### -What Gender is most affected by Breast Cancer?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/1603a55d-2c5a-4aad-ba39-fa7f4a231d8b)


Observation: We can see Breast Cancer has no Gender. 98.8% of breast cancer patients are women; men are about 1.2%. This is because women are at a higher risk of developing breast cancer. Some factors responsible for this are:

Hormonal factors: Women generally have higher estrogen and progesterone hormone levels than men.

Genetic factors: Certain inherited gene mutations, such as BRCA1 and BRCA2, are mostly common in women than men.

Breast tissue composition: Women have more glandular tissue in their breasts than men. Glandular tissue contains more cells that can potentially develop cancerous mutations.



#### -What is the age distribution of breast cancer cases?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/aaf462ae-d531-4575-b297-a6395196b0fc)


Observation: We can see the minimum age is at 29 and the maximum age is at 90.

The plot shows a spread of data within the age range 49 to 68 years. Which means Patieints with breast cancer are within these age range. According to WebMD, Your risk for breast cancer increases as you age. About 80% of women diagnosed with breast cancer each year are aged 45 or older.



#### -What Tumor stage is common or higher among the patients?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/b24c8b3e-841c-4089-bc09-b15c44397e3a)



Observation: The tumor stage refers to the extent or progression of cancer within the body. 

Tumor stage II is higher, with 55.4%, than stage III (23.8%) and stage I (20.8%). Which means we have more patients with stage II breast cancer. When breast cancer is in stage II, it is either still contained within the breast or the tumor has only reached nearby lymph nodes.



#### -What are the different histological types observed in the breast cancer patients?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/f8d8d691-cefd-4840-9673-47e09f07c1e8)


Histology, as used with breast cancer, is the study and analysis of microscopic features of breast tissue samples to identify the present kind and subtype of breast cancer. Diagnosis, categorization, and treatment planning for breast cancer patients depend heavily on histological analysis.

We can see Infiltrating Ductal Carcinoma accounts for 70.4% of breast cancer found in patients. Infiltrating Ductal Carcinoma refers to the uncontrolled growth of cancerous cells originating from the ducts of the breast tissue. It is the most common form of invasive breast cancer.

Infiltrating Lobular Carcinoma accounts for 26.1% of breast cancer found in patients. Infiltrating Lobular Carcinoma begins in the milk-producing glands (lobules) of the breast.

Mucinous Carcinoma accounts for 3.55 of breast cancer found in patients . Mucinous carcinoma is a rare type of cancer that primarily develops in the breast. This form of breast cancer tends to be less aggressive.



#### -What is the distribution of Estrogen Receptor (ER) status among the patients?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/5a9ad33e-aabd-4776-a4c4-3d270115a662)



Observation: We can see that 100% of Breast Cancer are Estrogen Positive. Which means the cancer cells grow in response to the Hormone Estrogen or express the Estrogen Receptor Protein (ER).

Knowing the hormone receptor status of your cancer helps doctors decide how to treat it.




### BIVARIATE ANALYSIS


#### -What is the ratio of Gender survivial on Breast Cancer?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/c4555c5c-68df-48e6-b2c8-72610ea68204)



Obseravation: According to the analysis, approximately 77.7% of women with breast cancer are reported as alive, indicating a higher proportion of women surviving the disease. Conversely, 21.1% of women are reported dead, representing the portion of women who did not survive.

On the other hand, the analysis shows that only 0.9% of men with breast cancer are reported as alive, indicating a significantly lower survival rate than women. Similarly, 0.3% of men are reported dead, representing the proportion of men who did not survive.

These results imply that women with breast cancer have a significantly better chance of surviving than men, according to the dataset. It's crucial to remember that these percentages are specific to the dataset under consideration and might not accurately reflect general survival rates or the representativeness of the total community of women and men with breast cancer.



#### -How does different tumor stages influence the outcome of patients?


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/183078a9-aecd-439b-a271-2dbe2dcd7cab)




Observation: From the visualization, we can see that

Stage I Breast Cancer: Among patients with stage I breast cancer, 15.8% are alive, while 5.0% have unfortunately died. This suggests that most patients with stage I breast cancer have a positive outcome, with a higher percentage of survivors than deaths.

Stage II Breast Cancer: In stage II breast cancer, the visualization reveals that 44.3% of patients are alive, while 11.1% have died. Although stage II has a higher percentage of deaths than stage I, it also has a significantly higher proportion of survivors. This indicates that while stage II breast cancer can result in more patient deaths, many patients still survive, leading to a higher overall survival rate than stage I.

Stage III Breast Cancer: The data shows that 18.5% of stage III breast cancer patients are alive, and 5.3% have died. Stage III has a relatively lower percentage of survivors and deaths than Stage II. However, it's important to note that the provided data visualization does not provide the whole picture, and further analysis would be required to understand the factors influencing the differences in patient outcomes between stage II and stage III.

The reason why stage II may have more deaths than stage III could be attributed to several factors. It is possible that stage II breast cancer, while generally considered less advanced than stage III, can still pose significant challenges and risks. The higher number of deaths in stage II could be due to various factors, including individual variations in tumor biology, aggressive subtypes, delayed diagnosis or treatment, or other patient-specific factors such as underlying health conditions or treatment response.



#### -Distribution of surgery types between male and female patients


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/db467c63-887d-4f62-ae23-29cfec333e3a)



Observation: "Other" Surgery Type: The visualization reveals that a higher percentage of females (30.5%) underwent the "Other" surgery type compared to males (0.3%). This suggests that the "Other" surgery type is more commonly performed in females for cancer treatment.

Modified Radical Mastectomy: The visualization indicates that a higher percentage of females (27.6%) underwent Modified Radical Mastectomy compared to males (0.6%). This implies that Modified Radical Mastectomy is predominantly chosen as a surgical option for females in the dataset.

Lumpectomy: The visualization shows that only females (21.4%) had Lumpectomy surgery; no males in the dataset had this type of surgery. This suggests that Lumpectomy is primarily performed as a breast-conserving surgery in females.

Simple Mastectomy: The visualization reveals that a significant percentage of females (19.4%) and males (0.3%) had surgery. This implies that Simple Mastectomy is performed in both genders, albeit with a higher prevalence in females.

These insights suggest that the choice of surgery type in cancer treatment exhibits gender-related patterns. The visualization indicates variations in the distribution of different surgery types between females and males. Factors such as tumor characteristics, treatment guidelines, patient preferences, and cultural influences may contribute to these observed differences.



### MULTIVARIATE ANALYSIS


#### -Visual showing the correlation between different variables


![image](https://github.com/HannatuGwabin/Exploratory-Data-Analysis-on-Breast-Cancer-Survival/assets/115185829/d3d6741b-b9fb-433a-9a62-8659710d7ba4)

​

Observation: There is a moderate strong correlation between Protein1 and Protein2

There is a moderate strong correlation between Protein1 and Protein4



### CONCLUSION


Exploratory Data Analysis on Breast Cancer Survival Data provides valuable insights into survival rates, age-related patterns, tumor characteristics, treatment modalities, hormone receptor status, and the impact of various factors on survival outcomes. These insights can aid in improving patient care, developing personalized treatment plans, identifying risk factors, and informing further research on breast cancer.



### NOTE 

Check out my notebook for more details. Thank you.
