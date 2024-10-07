
# Table of contents

- [Table of contents](#table-of-contents)
  - [Regression](#regression)
      - [UCI BlogFeedback](#uci-blogfeedback)
      - [UCI Communities and Crime](#uci-communities-and-crime)
      - [UCI Residential Building](#uci-residential-building)
      - [UCI Superconductivity](#uci-superconductivity)

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
| **Dataset URL**          | [UCI Superconductivity Data Dataset](https://archive.ics.uci.edu/ml/datasets/Superconductivty+Data)     