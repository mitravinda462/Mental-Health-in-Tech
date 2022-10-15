# Mental-Health-in-Tech
**Dataset:** OSMI Mental health in tech survey-2016, OSMI Mental health in tech survey-2017, OSMI Mental health in tech survey-2018, OSMI Mental health in tech survey-2019, OSMI Mental health in tech survey-2020, OSMI Mental health in tech survey-2021<br />
**Preprocess.ipynb:**<br />
Ensure that the following packages are installed and working:<br /> 
- pandas<br />
- numpy<br />
- seaborn<br />
- matplotlib<br />
- Sklearn<br />
- Warnings<br />
- plotly<br />
The code can be divided into 3 segments:<br />
- Data cleaning and preprocessing<br />
  - All column names are shortened and renamed to more accessible ones<br />
  - All columns having>50% NA are dropped<br />
  - Columns are encoded <br />
  - NA values are filled<br />
- Visualization<br />
  - Plot showing number of people who open about about illness in developed countries, different regions<br />
  - Proportions of gender based by region<br />
  - Mental health coverage provided by companies based on number of employees<br />
  - Benefit of conducting programs to address mental health in the workplace<br />
  - Employee awareness of coverage options<br />
  - Difficulties faced by employees in obtaining leave due to mental health issues<br />
  - Importance given to mental health<br />
  - Employer statistics<br />
  - Experience with previous employers<br />
  - Willingness to discuss mental health<br />
 - Correlation and ch-square tests<br />
  - Correlation and chi-square test between Mental health coverage provided by the company and the employee's comfort of discussing about their mental health with the supervisors<br />
  - Correlation and chi-square test between awareness of coverage and comfort in discussing with supervisor<br />
  - Correlation and chi-square test between help provided by previous employers and whether mental health was taken seriously<br />

**Mental_health_code.ipynb:**
<br />
Packages required:<br />
Same as preprocess.ipynb<br /> 

The code can be divided into 5 parts: <br />
- Preprocessing:<br />
  - Same as in preprocess.ipynb <br />
- KNN classifier:<br />
  - Splits the dataset into test and train <br />
  - Uses the diagnosis column as target <br />
  - Plots training and testing scores for different values of K to find optimum K <br />
  - Builds a classifier which predicts whether a person is likely be diagnosed as having a mental health issue or not<br />
  - Accuracy calculation<br />
- KMeans clustering:<br />
  - Performs K-means clustering on dataset to find optimum number of clusters using Elbow method and calinski harabasz score<br />
  - Perform clustering and check goodness using silhouette score and visualizer<br />
  - Plot the clustering for optimum k<br />
- Risk Classification<br />
  - Use columns columns on diagnosis and current mental health for each point in the different clusters to classify clusters as high, low and medium risk<br />
- Inferences<br />
  - Instances of Family history for people at different levels of risk<br />
  - Distribution of positive diagnoses among the three classes<br />
  - Levels of risk for people who don’t open up about their illness<br />
  - Risk levels for remote and non-remote workers<br />
  - Impact of negative reaction in workplace<br />


**prediction_model_mental_health.ipynb:**
<br>
The following classifiers were implemented:<br/>
1. K neighbors classifier<br/>
2. Logistic regression<br/>
3. Decision tree classifier<br/>
4. Random forest classifier<br/>
5. Ada boost classifier<br/>
6. XGB Classifier<br/>
7. Gradient boosting classifier<br/>

The following validations were performed:
1. K fold cross validation
2. Silhouette score
3. Calinski Harabasz score
4. Sum of squared errors

The following clustering models were implemented:
1. K means clustering
2. K means++
3. Partition around Medoids clustering
4. Agglomerative Hierarchical clustering
5. Gaussian mixture models
6. Spectral clustering
7. BIRCH clustering

Inferences
1. Family history of mental illness
2. Impact of past history of mental health disorder
3. Impact of age
4. Impact of gender
5. Impact of workplace social support
6. Pre nd post covid analysis:
  -Formal discussions on mental health by employers
  - Formal discussions on mental health by employers
  - Unsupportiveness towards mental health issues in workplace
  - Employees’ openness to discuss mental health issues in work-
place
- Requesting a mental health leave of absence
- Importance placed by employers on physical and mental health
-Supportiveness towards mental health issues in workplace
-Tech industry’s support for employees with mental health issues









