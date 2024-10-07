# Table of contents
- [Table of contents](#table-of-contents)
  - [Classification](#classification)
      - [Adult Income](#adult-income)
      - [Bank Marketing](#bank-marketing)
      - [Breast Cancer Wisconsin](#breast-cancer-wisconsin)
      - [Sarcoma](#sarcoma)
      - [Dota 2 Games](#dota-2-games)
      - [Earthquake](#earthquake)
      - [Heart Disease](#heart-disease)
      - [TCGA tumor](#tcga-tumor)
      - [Spambase](#spambase)
      - [Wine Quality](#wine-quality)

## Classification
#### Adult Income

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Adult (Census Income Dataset)                                                                                                                       |
| **Number of Instances**  | 48,842                                                                                                                                              |
| **Number of Features**   | 14                                                                                                                                                  |
| **Number of Classes**    | 2 (">50K", "<=50K")                                                                                                                                 |
| **Feature Types**        | Categorical, Integer                                                                                                                                |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Social Science                                                                                                                                      |
| **Has Missing Values?**  | Yes                                                                                                                                                |
| **Dataset Characteristics** | Multivariate                                                                                                                                  |
| **Dataset Origin**       | Extracted by Barry Becker from the 1994 U.S. Census Bureau database                                                                                  |
| **Prediction Task**      | Determine whether a person's annual income exceeds $50,000 based on various demographic attributes                                                  |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `age`: Continuous                                                                                                                                |
|                          | 2. `workclass`: Categorical (Private, Self-employed, Federal-gov, etc.)                                                                             |
|                          | 3. `fnlwgt`: Continuous                                                                                                                             |
|                          | 4. `education`: Categorical (Bachelors, HS-grad, Doctorate, etc.)                                                                                   |
|                          | 5. `education-num`: Continuous                                                                                                                     |
|                          | 6. `marital-status`: Categorical (Never-married, Divorced, etc.)                                                                                    |
|                          | 7. `occupation`: Categorical (Tech-support, Craft-repair, Sales, etc.)                                                                              |
|                          | 8. `relationship`: Categorical (Husband, Wife, Not-in-family, etc.)                                                                                 |
|                          | 9. `race`: Categorical (White, Asian-Pac-Islander, Black, etc.)                                                                                     |
|                          | 10. `sex`: Binary (Male, Female)                                                                                                                   |
|                          | 11. `capital-gain`: Continuous                                                                                                                     |
|                          | 12. `capital-loss`: Continuous                                                                                                                     |
|                          | 13. `hours-per-week`: Continuous                                                                                                                   |
|                          | 14. `native-country`: Categorical (United States, Mexico, Japan, etc.)                                                                              |
| **Dataset URL**          | [UCI Adult Dataset](https://archive.ics.uci.edu/ml/datasets/Adult)                                                                                 |


#### Bank Marketing

| **Property**             | **Details**                                                                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Bank Marketing                                                                                                                                  |
| **Number of Instances**  | 45,211                                                                                                                                          |
| **Number of Features**   | 16                                                                                                                                              |
| **Number of Classes**    | 2 ("yes", "no")                                                                                                                                 |
| **Feature Types**        | Categorical, Integer                                                                                                                            |
| **Associated Tasks**     | Classification                                                                                                                                  |
| **Subject Area**         | Business                                                                                                                                        |
| **Has Missing Values?**  | No                                                                                                                                              |
| **Dataset Characteristics** | Multivariate                                                                                                                            |
| **Dataset Origin**       | Direct marketing campaigns of a Portuguese banking institution                                                                                  |
| **Prediction Task**      | Predict if the client will subscribe to a term deposit (binary: "yes" or "no")                                                                  |
| **Attributes**           |                                                                                                                                                 |
|                          | 1. `age`: Integer                                                                                                                               |
|                          | 2. `job`: Categorical (e.g., admin, blue-collar, entrepreneur, etc.)                                                                            |
|                          | 3. `marital`: Categorical (married, divorced, single)                                                                                           |
|                          | 4. `education`: Categorical (basic, high school, university degree, etc.)                                                                       |
|                          | 5. `default`: Binary (has credit in default?)                                                                                                   |
|                          | 6. `balance`: Integer (average yearly balance in euros)                                                                                        |
|                          | 7. `housing`: Binary (has housing loan?)                                                                                                        |
|                          | 8. `loan`: Binary (has personal loan?)                                                                                                          |
|                          | 9. `contact`: Categorical (communication type, e.g., cellular, telephone)                                                                       |
|                          | 10. `day`: Date (last contact day of the month)                                                                                                 |
|                          | 11. `month`: Categorical (last contact month, e.g., jan, feb, etc.)                                                                             |
|                          | 12. `duration`: Integer (last contact duration in seconds)                                                                                      |
|                          | 13. `campaign`: Integer (number of contacts performed during this campaign and for this client)                                                 |
|                          | 14. `pdays`: Integer (days since last contacted from a previous campaign)                                                                       |
|                          | 15. `previous`: Integer (number of contacts before this campaign)                                                                               |
|                          | 16. `poutcome`: Categorical (outcome of previous marketing campaign)                                                                            |
| **Dataset URL**          | [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)                                                            |



#### Breast Cancer Wisconsin

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Breast Cancer Wisconsin (Diagnostic)                                                                                                                |
| **Number of Instances**  | 569                                                                                                                                                 |
| **Number of Features**   | 30                                                                                                                                                  |
| **Number of Classes**    | 2 ("M" for Malignant, "B" for Benign)                                                                                                               |
| **Feature Types**        | Real                                                                                                                                               |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Health and Medicine                                                                                                                                |
| **Has Missing Values?**  | No                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                 |
| **Dataset Origin**       | Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.                                                       |
| **Prediction Task**      | Classify tumors as malignant or benign based on characteristics of the cell nuclei present in the image.                                            |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `ID`: Identifier                                                                                                                                 |
|                          | 2. `Diagnosis`: Target variable (M = Malignant, B = Benign)                                                                                         |
|                          | 3. `radius_mean`: Continuous                                                                                                                       |
|                          | 4. `texture_mean`: Continuous                                                                                                                      |
|                          | 5. `perimeter_mean`: Continuous                                                                                                                    |
|                          | 6. `area_mean`: Continuous                                                                                                                         |
|                          | 7. `smoothness_mean`: Continuous                                                                                                                   |
|                          | 8. `compactness_mean`: Continuous                                                                                                                  |
|                          | 9. `concavity_mean`: Continuous                                                                                                                    |
|                          | 10. `concave points_mean`: Continuous                                                                                                              |
|                          | 11. `symmetry_mean`: Continuous                                                                                                                    |
|                          | 12. `fractal_dimension_mean`: Continuous                                                                                                           |
| **Dataset URL**          | [UCI Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)) |


#### Sarcoma

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Sarcoma  Chibon                                                                                                             |
| **Number of Instances**  | 310                                                                                                                                                 |
| **Number of Features**   | 30                                                                                                                                                  |
| **Number of Classes**    | 2                                                                                           |
| **Feature Types**        | Real                                                                                                                                               |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Health and Medicine                                                                                                                                |
| **Has Missing Values?**  | No                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                 |
| **Dataset Origin**       | Tissue sarcomas with no recurrent chromosomal translocations from the French Sarcoma Group (FSG) database.                                                       |
| **Prediction Task**      | Classify based on gene expression underlying the tumor biology.                                            |
| | **Attributes**           | 2284 attributes representing physical and chemical properties (e.g., atomic mass, entropy, and density).                                                                                                                                |
| **Dataset URL**          | [Expression data from Complex genetics sarcomas Dataset](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE21050) |


#### Dota 2 Games

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Dota2 Games Results                                                                                                                                 |
| **Number of Instances**  | 102,944                                                                                                                                             |
| **Number of Features**   | 115                                                                                                                                                |
| **Number of Classes**    | 2 (1 for Team 1 win, -1 for Team 2 win)                                                                                                             |
| **Feature Types**        | Binary and Integer                                                                                                                                  |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Games                                                                                                                                               |
| **Has Missing Values?**  | No                                                                                                                                                  |
| **Dataset Characteristics** | Multivariate                                                                                                                                 |
| **Dataset Origin**       | Matches played over a 2-hour period on 13th August 2016.                                                                                             |
| **Prediction Task**      | Predict the outcome of a Dota 2 game based on selected heroes and game attributes.                                                                  |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `win`: Target variable (1 = Team 1 wins, -1 = Team 2 wins)                                                                                       |
|                          | 2. `clusterid`: Integer (related to location)                                                                                                       |
|                          | 3. `gamemode`: Integer (Game mode)                                                                                                                  |
|                          | 4. `gametype`: Integer (Game type)                                                                                                                  |
|                          | 5-115. `hero1` to `hero113`: Binary values indicating which heroes were chosen by each team.                                                        |
| **Dataset URL**          | [UCI Dota2 Games Results Dataset](https://archive.ics.uci.edu/ml/datasets/Dota2+Games+Results)                                                       |

#### Earthquake

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Nepal Earthquake                                                                                                                                   |
| **Number of Instances**  | 260,601                                                                                                                                             |
| **Number of Features**   | 39                                                                                                                                                 |
| **Number of Classes**    | 3                                                                                                                                                  |
| **Feature Types**        | Real, Categorical, Binary, and Integer                                                                                                              |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Natural disaster                                                                                                                                   |
| **Has Missing Values?**  | No                                                                                                                                                  |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | The data was collected through surveys by Kathmandu Living Labs and the Central Bureau of Statistics, under the National Planning Commission Secretariat of Nepal. This is one of the largest post-disaster datasets collected, containing information on earthquake impacts, household conditions, and socio-economic-demographic statistics. |
| **Prediction Task**      | Based on building location and construction, predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal.               |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `geo_level_1_id`: (int) Geographic region (level 1, 0-30)                                                                                       |
|                          | 2. `geo_level_2_id`: (int) Geographic sub-region (level 2, 0-1427)                                                                                 |
|                          | 3. `geo_level_3_id`: (int) Geographic sub-region (level 3, 0-12567)                                                                                |
|                          | 4. `count_floors_pre_eq`: (int) Number of floors before the earthquake                                                                             |
|                          | 5. `age`: (int) Age of the building in years                                                                                                       |
|                          | 6. `area_percentage`: (int) Normalized area of the building footprint                                                                              |
|                          | 7. `height_percentage`: (int) Normalized height of the building                                                                                    |
|                          | 8. `land_surface_condition`: (categorical) Surface condition of the land (n, o, t)                                                                 |
|                          | 9. `foundation_type`: (categorical) Foundation type (h, i, r, u, w)                                                                                |
|                          | 10. `roof_type`: (categorical) Roof type (n, q, x)                                                                                                 |
|                          | 11. `ground_floor_type`: (categorical) Ground floor type (f, m, v, x, z)                                                                           |
|                          | 12. `other_floor_type`: (categorical) Upper floor type (j, q, s, x)                                                                                |
|                          | 13. `position`: (categorical) Position of the building (j, o, s, t)                                                                                |
|                          | 14. `plan_configuration`: (categorical) Building plan configuration (a, c, d, f, m, n, o, q, s, u)                                                 |
|                          | 15. `has_superstructure_adobe_mud`: (binary) Adobe/Mud superstructure (1 = Yes, 0 = No)                                                            |
|                          | 16. `has_superstructure_mud_mortar_stone`: (binary) Mud Mortar - Stone superstructure (1 = Yes, 0 = No)                                            |
|                          | 17. `has_superstructure_stone_flag`: (binary) Stone superstructure (1 = Yes, 0 = No)                                                               |
|                          | 18. `has_superstructure_cement_mortar_stone`: (binary) Cement Mortar - Stone superstructure (1 = Yes, 0 = No)                                      |
|                          | 19. `has_superstructure_mud_mortar_brick`: (binary) Mud Mortar - Brick superstructure (1 = Yes, 0 = No)                                            |
|                          | 20. `has_superstructure_cement_mortar_brick`: (binary) Cement Mortar - Brick superstructure (1 = Yes, 0 = No)                                      |
|                          | 21. `has_superstructure_timber`: (binary) Timber superstructure (1 = Yes, 0 = No)                                                                  |
|                          | 22. `has_superstructure_bamboo`: (binary) Bamboo superstructure (1 = Yes, 0 = No)                                                                  |
|                          | 23. `has_superstructure_rc_non_engineered`: (binary) Non-engineered reinforced concrete (1 = Yes, 0 = No)                                           |
|                          | 24. `has_superstructure_rc_engineered`: (binary) Engineered reinforced concrete (1 = Yes, 0 = No)                                                  |
|                          | 25. `has_superstructure_other`: (binary) Other superstructure materials (1 = Yes, 0 = No)                                                          |
|                          | 26. `legal_ownership_status`: (categorical) Legal ownership status (a, r, v, w)                                                                    |
|                          | 27. `count_families`: (int) Number of families in the building                                                                                     |
|                          | 28. `has_secondary_use`: (binary) Secondary use of the building (1 = Yes, 0 = No)                                                                  |
|                          | 29. `has_secondary_use_agriculture`: (binary) Secondary use for agriculture (1 = Yes, 0 = No)                                                      |
|                          | 30. `has_secondary_use_hotel`: (binary) Secondary use as a hotel (1 = Yes, 0 = No)                                                                 |
|                          | 31. `has_secondary_use_rental`: (binary) Secondary use for rental purposes (1 = Yes, 0 = No)                                                       |
|                          | 32. `has_secondary_use_institution`: (binary) Secondary use as an institution (1 = Yes, 0 = No)                                                    |
|                          | 33. `has_secondary_use_school`: (binary) Secondary use as a school (1 = Yes, 0 = No)                                                               |
|                          | 34. `has_secondary_use_industry`: (binary) Secondary use for industry (1 = Yes, 0 = No)                                                            |
|                          | 35. `has_secondary_use_health_post`: (binary) Secondary use as a health post (1 = Yes, 0 = No)                                                     |
|                          | 36. `has_secondary_use_gov_office`: (binary) Secondary use as a government office (1 = Yes, 0 = No)                                                |
|                          | 37. `has_secondary_use_police`: (binary) Secondary use as a police station (1 = Yes, 0 = No)                                                       |
|                          | 38. `has_secondary_use_other`: (binary) Secondary use for other purposes (1 = Yes, 0 = No)                                                         |
| **Dataset URL**          | [Richter's Predictor: Modeling Earthquake Damage](https://www.drivendata.org/competitions/57/nepal-earthquake/page/136/)  |


#### Heart Disease

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Indicators of Heart Disease                                                                                                                        |
| **Number of Instances**  | 319,795                                                                                                                                             |
| **Number of Features**   | 18                                                                                                                                                |
| **Number of Classes**    | 2                                                                                                                                                |
| **Feature Types**        | Real, Categorical, Binary, Integer                                                                                                                  |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Healthcare                                                                                                                                            |
| **Has Missing Values?**  | No                                                                                                                                                  |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | The data was collected as part of the annual CDC Behavioral Risk Factor Surveillance System (BRFSS) survey, a system used to monitor health-related risk behaviors in the US.                                                                                         |
| **Prediction Task**      | Predict whether a patient has heart disease based on a variety of health indicators.                                                                 |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `HeartDisease`: (binary) Target variable indicating if the patient has heart disease (1 = Yes, 0 = No)                                           |
|                          | 2. `BMI`: (real) Body Mass Index of the patient                                                                                                     |
|                          | 3. `Smoking`: (binary) Whether the patient has smoked at least 100 cigarettes in their lifetime (1 = Yes, 0 = No)                                   |
|                          | 4. `AlcoholDrinking`: (binary) Whether the patient is a heavy drinker (consuming more than 14 drinks per week for men, and more than 7 for women) (1 = Yes, 0 = No) |
|                          | 5. `Stroke`: (binary) Whether the patient has ever had a stroke (1 = Yes, 0 = No)                                                                  |
|                          | 6. `PhysicalHealth`: (int) Number of days in the past 30 days where the patient’s physical health was not good                                      |
|                          | 7. `MentalHealth`: (int) Number of days in the past 30 days where the patient’s mental health was not good                                          |
|                          | 8. `DiffWalking`: (binary) Whether the patient has difficulty walking (1 = Yes, 0 = No)                                                            |
|                          | 9. `Sex`: (categorical) Sex of the patient (Male, Female)                                                                                           |
|                          | 10. `AgeCategory`: (categorical) Age category of the patient (18-24, 25-29, 30-34, ..., 80 or older)                                                |
|                          | 11. `Race`: (categorical) Race of the patient (White, Black, Asian, American Indian/Alaskan Native, Other, Hispanic)                                |
|                          | 12. `Diabetic`: (categorical) Whether the patient is diabetic (Yes, No, No, borderline diabetes, Yes during pregnancy)                              |
|                          | 13. `PhysicalActivity`: (binary) Whether the patient engages in physical activity in the past 30 days other than their regular job (1 = Yes, 0 = No) |
|                          | 14. `GenHealth`: (categorical) General health condition of the patient (Excellent, Very good, Good, Fair, Poor)                                     |
|                          | 15. `SleepTime`: (int) Average number of hours of sleep per night                                                                                   |
|                          | 16. `Asthma`: (binary) Whether the patient has been diagnosed with asthma (1 = Yes, 0 = No)                                                        |
|                          | 17. `KidneyDisease`: (binary) Whether the patient has been diagnosed with kidney disease (1 = Yes, 0 = No)                                         |
|                          | 18. `SkinCancer`: (binary) Whether the patient has been diagnosed with skin cancer (1 = Yes, 0 = No)                                                |
| **Dataset URL**          | [Indicators of Heart Disease](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)                                                                 |


#### TCGA tumor

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | TCGA (The Cancer Genome Atlas) - Predicting Tumor Status                                                                                           |
| **Number of Instances**  | 801                                                                                                                                                 |
| **Number of Features**   | 42,754                                                                                                                                              |
| **Number of Classes**    | 2                                                                                                                                                   |
| **Feature Types**        | Real, Binary, Categorical                                                                                                                           |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Genomics, Healthcare                                                                                                                                 |
| **Has Missing Values?**  | No                                                                                                                                                  |
| **Dataset Characteristics** | Multivariate                                                                                                                                   |
| **Dataset Origin**       | The data originates from The Cancer Genome Atlas (TCGA), which collects multi-dimensional data from thousands of cancer patients. This dataset includes gene expression profiles and clinical data from patients, and is used to predict tumor status.                       |
| **Prediction Task**      | Predict whether a sample is from a **tumor** or **normal tissue** based on gene expression levels.                                                  |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `Tumor`: (binary) Target variable, indicates whether the sample is from a tumor (1 = Tumor, 0 = Normal)                                          |
|                          | 2. `Gene_00001` to `Gene_042754`: (real) Gene expression levels for 42,754 genes. The values are numerical and represent the relative expression of each gene in a sample.               |
| **Dataset URL**          | [Gene expression cancer RNA-Seq](https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq)                                                                 |

#### Spambase

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Spambase                                                                                                                                            |
| **Number of Instances**  | 4,601                                                                                                                                               |
| **Number of Features**   | 57                                                                                                                                                  |
| **Number of Classes**    | 2 (Spam or Not Spam)                                                                                                                                |
| **Feature Types**        | Integer, Real                                                                                                                                       |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Computer Science                                                                                                                                   |
| **Has Missing Values?**  | Yes                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                 |
| **Dataset Origin**       | Emails collected from spam reports and non-spam emails from work and personal correspondence.                                                        |
| **Prediction Task**      | Determine if an email is spam or not based on word frequencies and character patterns.                                                              |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `word_freq_make`: Continuous (frequency of "make")                                                                                                 |
|                          | 2. `word_freq_address`: Continuous (frequency of "address")                                                                                           |
|                          | 3. `char_freq_$`: Continuous (frequency of character `$`)                                                                                             |
|                          | 4. `capital_run_length_average`: Average length of uninterrupted sequences of capital letters                                                        |
|                          | 5. `capital_run_length_longest`: Length of longest uninterrupted sequence of capital letters                                                         |
|                          | 6. `capital_run_length_total`: Total number of capital letters                                                                                       |
| **Dataset URL**          | [UCI Spambase Dataset](https://archive.ics.uci.edu/ml/datasets/Spambase)                                                                |


#### Wine Quality

| **Property**             | **Details**                                                                                                                                          |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Wine Quality (Red & White)                                                                                                                           |
| **Number of Instances**  | Red wine: 1,599; White wine: 4,898                                                                                                                    |
| **Number of Features**   | 11                                                                                                                                                   |
| **Number of Classes**    | Quality score between 0 and 10                                                                                                                       |
| **Feature Types**        | Real                                                                                                                                                 |
| **Associated Tasks**     | Classification, Regression                                                                                                                           |
| **Subject Area**         | Business, Chemistry                                                                                                                                  |
| **Has Missing Values?**  | No                                                                                                                                                   |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | Red and white variants of Portuguese "Vinho Verde" wine from the north of Portugal.                                                                   |
| **Prediction Task**      | Model wine quality based on physicochemical tests and sensory data (quality score).                                                                   |
| **Attributes**           |                                                                                                                                                      |
|                          | 1. `fixed_acidity`: Continuous                                                                                                                       |
|                          | 2. `volatile_acidity`: Continuous                                                                                                                    |
|                          | 3. `citric_acid`: Continuous                                                                                                                         |
|                          | 4. `residual_sugar`: Continuous                                                                                                                      |
|                          | 5. `chlorides`: Continuous                                                                                                                           |
|                          | 6. `free_sulfur_dioxide`: Continuous                                                                                                                 |
|                          | 7. `total_sulfur_dioxide`: Continuous                                                                                                                |
|                          | 8. `density`: Continuous                                                                                                                             |
|                          | 9. `pH`: Continuous                                                                                                                                  |
|                          | 10. `sulphates`: Continuous                                                                                                                          |
|                          | 11. `alcohol`: Continuous                                                                                                                            |
|                          | 12. `quality`: Target variable (0-10 score based on sensory data)                                                                                     |
| **Dataset URL**          | [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)                                                                 |
