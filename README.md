# Mental-Health-in-Tech


**Introduction**

In 2016, according to Open Sourcing Mental Illness (OSMI) organization’s survey, 51% of tech professionals had been diagnosed with a mental health condition. While the factors that impact a person’s mental wellness differ from individual to individual, there are various risk factors for mental health of employees that may be present in their work environment. Major risk factors can be identified as minimal support for employees, insufficient health and safety policies, inflexible working hours, poor communication, poor management etc. Thus, it is important for employers or organizations to work towards reducing the work-related stress factors along with promoting and
supporting mental health in workplace.

This study aims to predict employees’ disposition of progressing to a mental health issue, but also to identify and understand the factors influencing employees’ mental health in their workplaces. Various classification models were implemented to predict whether or not an employee could be diagnosed with a mental health issue. Similarly, a risk indicator was modeled using various clustering techniques. The employees were fractionated into 3 clusters representing different levels of risk of the employees progressing to a mental health issue. Further, the characteristics of the risk clusters and factors
affecting the risk were studied. Researches specific to different parts of the world have reported an increase in the mental health symptoms and a deterioration in mental health after the onset of COVID-19. COVID-19 has caused tremendous human and humanitarian challenges in workplace causing major changes in the work culture. The pandemic having seeded quarantine, lockdown, loss of physical contact with friends and co-workers, uncertain employment, work from home and more has brought in various risk factors that pose concerns for employees’ mental wellness. Thus, the study is tied together with the current mental health scenario through a multi-year analysis on the trends in mental health in workplace before and after the onset of COVID-19.
<br />

**Dataset:** 

OSMI Mental health in tech survey-2016 (https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)<br>
OSMI Mental health in tech survey-2017(https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2017)<br>
OSMI Mental health in tech survey-2018(https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2018)<br>
OSMI Mental health in tech survey-2019 (https://www.kaggle.com/datasets/osmihelp/osmi-mental-health-in-tech-survey-2019)<br>
OSMI Mental health in tech survey-2020 (https://www.kaggle.com/datasets/osmihelp/osmi-2020-mental-health-in-tech-survey-results)<br>
OSMI Mental health in tech survey-2021 (https://www.kaggle.com/datasets/osmihelp/osmh-2021-mental-health-in-tech-survey-results)
<br />

**System design**

The first step in the system design is pre-processing the OSMI Mental Health in Tech Survey 2016 data set. The data pre-processing was commenced by cleaning the data and renaming the column names. It was then followed by handling the inconsistent categorical values and encoding the categorical and ordinal variables. Exploratory Data Analysis (EDA) was conducted to understand the data set and extract
insights from it. Based on the knowledge learned from EDA, feature selection was performed to identify and select the features that are relevant and appropriate to build the intended models. The prediction model was built to predict the employees’ possibility of being diagnosed with a mental health issue. The risk indicator model was then built to identify and understand the risk factors influencing the employees’ mental health. The results obtained were evaluated and analysed along with obtaining appropriate inferences. Finally, the datasets of OSMI Mental Health in Tech Survey 2017, 2018, 2019, 2020 and 2021 were studied to understand and infer the trends in the mental health scenariopre- and post-COVID-19.
<br />

**Preprocessing**

 As the first step, the data set was cleaned. Columns with over 50% missing values were dropped. The rest of the missing values were imputed with appropriate values based on their columns. This was followed by renaming all the columns in order to make them easily referenceable. Post data cleaning, the data present in the data set belonged to one among the following types- numerical, categorical, ordinal or nominal. The categorical columns had multiple instances belonging to the same category but with inconsistent category-names. These were handled by imputing the instances belonging to the same category with the same category-name. Similarly, outliers present in the numerical columns were handled by replacing them with their column average. Finally, all the categorical and ordinal data
were encoded.
<br />

**Classifiers**

The following classifiers were implemented:<br/>
1. K neighbors classifier<br/>
2. Logistic regression<br/>
3. Decision tree classifier<br/>
4. Random forest classifier<br/>
5. Ada boost classifier<br/>
6. XGB Classifier<br/>
7. Gradient boosting classifier<br/>

**Clustering models**

The following clustering models were implemented:
1. K means clustering
2. K means++
3. Partition around Medoids clustering
4. Agglomerative Hierarchical clustering
5. Gaussian mixture models
6. Spectral clustering
7. BIRCH clustering

**Inferences**

Inferences were drawn on the following categories:
1. Family history of mental illness
2. Impact of past history of mental health disorder
3. Impact of age
4. Impact of gender
5. Impact of workplace social support
6. Pre and post covid analysis:

  -Formal discussions on mental health by employers
  - Formal discussions on mental health by employers
  - Unsupportiveness towards mental health issues in workplace
  - Employees’ openness to discuss mental health issues in work-
place
- Requesting a mental health leave of absence
- Importance placed by employers on physical and mental health
-Supportiveness towards mental health issues in workplace
-Tech industry’s support for employees with mental health issues

**Evaluation methods**

The following validations were performed:
1. K fold cross validation
2. Silhouette score
3. Calinski Harabasz score
4. Sum of squared errors








