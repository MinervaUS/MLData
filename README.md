# MLData


## Dataset Index

- [Classification](#classification)
  - [Adult Income](#adult-income)
  - [Bank Marketing](#bank-marketing)
  - [Breast Cancer](#breast-cancer)
  - [Cancer Gene](#cancer-gene)
  - [Dota 2](#dota-2)
  - [Earthquake](#earthquake)
  - [Heart](#heart)
  - [Spambase](#spambase)
  - [TCGA](#tcga)
  - [Water Pump](#water-pump)
  - [Wine Red](#wine-red)
  - [Wine White](#wine-white)

- [Regression](#regression)
  - [Blog Feedback](#blog-feedback)
  - [Crime](#crime)
  - [Residential Building](#residential-building)
  - [Superconductor](#superconductor)

- [Time Series](#time-series)
  - Demand
    - [Australia Demand](#australia-demand)
    - [Spain Demand](#spain-demand)

  - Energy
    - [ETTh1](#etth1)
    - [ETTh2](#etth2)

  - Finance
    - [CIF 2016 o12](#cif-2016-o12)
    - [CIF 2016 o6](#cif-2016-o6)
    - [Exchange Rate](#exchange-rate)
    - [M3](#m3)
    - [M4](#m4)

  - Meteorology
    - [Castro Verde](#castro-verde)
    - [Estremoz](#estremoz)
    - [Herdade Lameiroes](#herdade-lameiroes)
    - [Herdade Outeiro](#herdade-outeiro)
    - [Mira Odemira](#mira-odemira)
    - [Quinta Saude](#quinta-saude)
    - [Serpa](#serpa)
    - [Viana Alentejo](#viana-alentejo)
    - [Vidigueira](#vidigueira)

  - Pollution
    - [Aljarafe](#aljarafe)
    - [Asomadilla](#asomadilla)
    - [Bermejales](#bermejales)
    - [Global CO](#global-co)
    - [Ronda del Valle](#ronda-del-valle)
    - [Torneo](#torneo)

  - Traffic
    - [Tourism](#tourism)
    - [Traffic LA Metro](#traffic-la-metro)
    - [Traffic Perms Bay](#traffic-perms-bay)
    - [Traffic](#traffic)
    - [Wiki Web Traffic](#wiki-web-traffic)


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


#### UCI Heart Disease

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Heart Disease                                                                                                                                        |
| **Number of Instances**  | 303                                                                                                                                                 |
| **Number of Features**   | 13 (commonly used subset)                                                                                                                           |
| **Number of Classes**    | 2 (presence or absence of heart disease)                                                                                                            |
| **Feature Types**        | Categorical, Integer, Real                                                                                                                          |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Health and Medicine                                                                                                                                |
| **Has Missing Values?**  | Yes                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                 |
| **Dataset Origin**       | The dataset was compiled from four sources: Cleveland, Hungary, Switzerland, and VA Long Beach databases.                                            |
| **Prediction Task**      | Classify whether a patient has heart disease or not.                                                                                                 |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `age`: Integer                                                                                                                                   |
|                          | 2. `sex`: Categorical (1 = male, 0 = female)                                                                                                        |
|                          | 3. `cp`: Categorical (chest pain type: 1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)                               |
|                          | 4. `trestbps`: Integer (resting blood pressure in mm Hg)                                                                                            |
|                          | 5. `chol`: Integer (serum cholesterol in mg/dl)                                                                                                     |
|                          | 6. `fbs`: Categorical (fasting blood sugar > 120 mg/dl: 1 = true, 0 = false)                                                                         |
|                          | 7. `restecg`: Categorical (resting electrocardiographic results)                                                                                     |
|                          | 8. `thalach`: Integer (maximum heart rate achieved)                                                                                                  |
|                          | 9. `exang`: Categorical (exercise induced angina: 1 = yes, 0 = no)                                                                                   |
|                          | 10. `oldpeak`: Integer (ST depression induced by exercise relative to rest)                                                                          |
|                          | 11. `slope`: Categorical (the slope of the peak exercise ST segment)                                                                                 |
|                          | 12. `ca`: Integer (number of major vessels colored by fluoroscopy)                                                                                   |
|                          | 13. `thal`: Categorical (3 = normal, 6 = fixed defect, 7 = reversible defect)                                                                         |
| **Dataset URL**          | [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)                                                                 |

#### UCI Statlog (Heart)

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Statlog (Heart)                                                                                                                                     |
| **Number of Instances**  | 270                                                                                                                                                 |
| **Number of Features**   | 13                                                                                                                                                  |
| **Number of Classes**    | 2 (absence or presence of heart disease)                                                                                                            |
| **Feature Types**        | Categorical, Real                                                                                                                                   |
| **Associated Tasks**     | Classification                                                                                                                                      |
| **Subject Area**         | Health and Medicine                                                                                                                                |
| **Has Missing Values?**  | No                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                 |
| **Dataset Origin**       | The dataset contains information about patients' health metrics such as age, cholesterol levels, and ECG results.                                    |
| **Prediction Task**      | Classify the presence or absence of heart disease.                                                                                                   |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `age`: Continuous                                                                                                                                |
|                          | 2. `sex`: Binary                                                                                                                                   |
|                          | 3. `chest pain type`: Categorical                                                                                                                  |
|                          | 4. `resting blood pressure`: Continuous                                                                                                            |
|                          | 5. `serum cholesterol`: Continuous                                                                                                                 |
|                          | 6. `fasting blood sugar`: Binary (fasting blood sugar > 120 mg/dl)                                                                                  |
|                          | 7. `resting electrocardiographic results`: Categorical                                                                                              |
|                          | 8. `maximum heart rate`: Continuous                                                                                                                |
|                          | 9. `exercise induced angina`: Binary                                                                                                               |
|                          | 10. `oldpeak`: Continuous                                                                                                                          |
|                          | 11. `slope`: Categorical                                                                                                                           |
|                          | 12. `number of major vessels`: Categorical                                                                                                         |
|                          | 13. `thal`: Categorical                                                                                                                            |
| **Dataset URL**          | [UCI Statlog (Heart) Dataset](https://archive.ics.uci.edu/ml/datasets/Statlog+(Heart))                                                              |


#### UCI Spambase

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


#### UCI Wine Quality

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

These datasets can be used for both classification and regression tasks, with the target being the wine quality, scored between 0 (very poor) and 10 (very excellent).

## Regression

#### UCI BlogFeedback

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | BlogFeedback                                                                                                                                         |
| **Number of Instances**  | 60,021                                                                                                                                              |
| **Number of Features**   | 281                                                                                                                                                 |
| **Number of Classes**    | N/A (Regression task)                                                                                                                               |
| **Feature Types**        | Integer, Real                                                                                                                                       |
| **Associated Tasks**     | Regression                                                                                                                                          |
| **Subject Area**         | Social Science                                                                                                                                      |
| **Has Missing Values?**  | No                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | Extracted from blog posts to predict the number of comments a post will receive in the next 24 hours.                                                |
| **Prediction Task**      | Predict the number of comments a blog post will receive within the next 24 hours based on the extracted features.                                     |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `1...50`: Statistics (average, std, min, max, median) of various attributes for the source of the blog post                                       |
|                          | 2. `51...55`: Comment-related features before the base time                                                                                          |
|                          | 3. `56...60`: Link (trackback)-related features                                                                                                      |
|                          | 4. `61...280`: Various features including text and time-related attributes                                                                           |
|                          | 5. `281`: Target variable (number of comments in the next 24 hours)                                                                                  |
| **Dataset URL**          | [UCI BlogFeedback Dataset](https://archive.ics.uci.edu/ml/datasets/BlogFeedback)                                                                      |

This dataset is used for regression tasks to predict the popularity of blog posts based on past engagement data.

#### UCI Communities and Crime

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Communities and Crime                                                                                                                               |
| **Number of Instances**  | 1,994 (normalized version); 2,215 (unnormalized version)                                                                                              |
| **Number of Features**   | 128 (normalized version); 147 (unnormalized version)                                                                                                  |
| **Number of Classes**    | N/A (Regression task)                                                                                                                               |
| **Feature Types**        | Categorical, Real                                                                                                                                   |
| **Associated Tasks**     | Regression                                                                                                                                          |
| **Subject Area**         | Social Science                                                                                                                                      |
| **Has Missing Values?**  | Yes (several attributes contain missing values)                                                                                                     |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | Data combined from multiple sources: 1990 U.S. Census, 1990 Law Enforcement Management and Administrative Statistics (LEMAS) survey, and 1995 FBI Uniform Crime Reporting (UCR) database. |
| **Prediction Task**      | Predict the number of violent crimes per capita for a given community.                                                                              |
| **Attributes**           |                                                                                                                                                     |
|                          | 1. `state`: Categorical (state code)                                                                                                               |
|                          | 2. `communityname`: Categorical (community name)                                                                                                    |
|                          | 3. `population`: Real                                                                                                                               |
|                          | 4. `householdsize`: Real                                                                                                                            |
|                          | 5. `racepctblack`: Real (percentage of population that is black)                                                                                    |
|                          | 6. `racePctWhite`: Real (percentage of population that is white)                                                                                    |
|                          | 7. `agePct12t21`: Real (percentage of population aged 12–21)                                                                                        |
|                          | 8. `agePct65up`: Real (percentage of population aged 65 and older)                                                                                   |
|                          | ...                                                                                                                                                |
|                          | 147. `ViolentCrimesPerPop`: Target variable (number of violent crimes per 100K population)                                                          |
| **Dataset URL**          | [UCI Communities and Crime Dataset](https://archive.ics.uci.edu/datasets?search=85)                                                                 |

This dataset is used for predicting the number of violent crimes per capita in different communities within the United States based on socio-economic and law enforcement data【64†source】.


#### UCI Residential Building 

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Residential Building                                                                                                                                |
| **Number of Instances**  | 372                                                                                                                                                 |
| **Number of Features**   | 105                                                                                                                                                 |
| **Number of Classes**    | N/A (Regression task)                                                                                                                               |
| **Feature Types**        | Real                                                                                                                                                |
| **Associated Tasks**     | Regression                                                                                                                                          |
| **Subject Area**         | Computer Science, Real Estate                                                                                                                       |
| **Has Missing Values?**  | No                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | The dataset includes construction cost, sale prices, and project variables for single-family residential apartments in Tehran, Iran.                 |
| **Prediction Task**      | Predict construction costs and sale prices of residential buildings based on various project and economic variables.                                                                        |
| **Attributes**           | 8 project physical and financial variables, 19 economic variables with 5 time lags each (totaling 95), and 2 output variables (construction costs and sale prices).                        |
| **Dataset URL**          | [UCI Residential Building Dataset](https://archive.ics.uci.edu/dataset/437/residential+building)                                                               |

#### UCI Superconductivity

| **Property**             | **Details**                                                                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                 | Superconductivity Data                                                                                                                              |
| **Number of Instances**  | 21,263                                                                                                                                              |
| **Number of Features**   | 81                                                                                                                                                  |
| **Number of Classes**    | N/A (Regression task)                                                                                                                               |
| **Feature Types**        | Real                                                                                                                                                |
| **Associated Tasks**     | Regression                                                                                                                                          |
| **Subject Area**         | Physics, Chemistry                                                                                                                                  |
| **Has Missing Values?**  | No                                                                                                                                                 |
| **Dataset Characteristics** | Multivariate                                                                                                                                    |
| **Dataset Origin**       | Features were extracted from superconductors to predict critical temperature based on material properties.                                           |
| **Prediction Task**      | Predict the critical temperature of superconductors.                                                                                                 |
| **Attributes**           | 81 attributes representing physical and chemical properties (e.g., atomic mass, entropy, and density).                                               |
| **Dataset URL**          | [UCI Superconductivity Data Dataset](https://archive.ics.uci.edu/ml/datasets/Superconductivty+Data)                                                                          |

# Time Series
