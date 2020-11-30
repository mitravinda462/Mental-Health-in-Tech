# Mental-Health-in-Tech
Dataset: OSMI Mental health in tech survey-2016<br />
Preprocess.ipynb:
Ensure that the following packages are installed and working: 
pandas
numpy
seaborn
matplotlib
Sklearn
Warnings
plotly

The code can be divided into 3 segments:
Data cleaning and preprocessing
All column names are shortened and renamed to more accessible ones
All columns having>50% NA are dropped
Columns are encoded 
NA values are filled
Visualization
Plot showing number of people who open about about illness in developed countries, different regions
Proportions of gender based by region
Mental health coverage provided by companies based on number of employees
Benefit of conducting programs to address mental health in the workplace
Employee awareness of coverage options
Difficulties faced by employees in obtaining leave due to mental health issues
Importance given to mental health
Employer statistics
Experience with previous employers
Willingness to discuss mental health
Correlation and ch-square tests
Correlation and chi-square test between Mental health coverage provided by the company and the employee's comfort of discussing about their mental health with the supervisors
Correlation and chi-square test between awareness of coverage and comfort in discussing with supervisor
Correlation and chi-square test between help provided by previous employers and whether mental health was taken seriously

Mental_health_code.ipynb:
Packages required:
Same as preprocess.ipynb and 

The code can be divided into _ parts:
Preprocessing:
Same as in preprocess.ipynb
KNN classifier:
Splits the dataset into test and train
Uses the diagnosis column as target
Plots training and testing scores for different values of K to find optimum K
Builds a classifier which predicts whether a person is likely be diagnosed as having a mental health issue or not
Accuracy calculation
K-Means clustering:
Performs K-means clustering on dataset to find optimum number of clusters using Elbow method and calinski harabasz score
Perform clustering and check goodness using silhouette score and visualizer
Plot the clustering for optimum k
Risk Classification
Use columns columns on diagnosis and current mental health for each point in the different clusters to classify clusters as high, low and medium risk
Inferences
Instances of Family history for people at different levels of risk
Distribution of positive diagnoses among the three classes
Levels of risk for people who don’t open up about their illness
Risk levels for remote and non-remote workers
Impact of negative reaction in workplace






