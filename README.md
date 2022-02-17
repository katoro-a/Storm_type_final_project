# Storm_type_final_project
Data sets were taken from the following link: https://www.ncei.noaa.gov/pub/data/swdi/stormevents/
# Objective/Question 
- Develop a classification machine learning model to predict EVENT_TYPE using the dataset taken from national centers for environmental information(NOAA). The dataset has information about when the event happened:duration, month, year, time,where it happened:i.e. state, county, damage caused by the event:i.e. deaths, cost of damage to both
      crops and property, injuries.
 # Focusing on the following years 
  - Consecutive years were not selected as the location files were unavalible.
      - 2008
      - 2010
      - 2011
      - 2012
      - 2015
      - 2017
      - 2020
      - 2021  

# Looking at the following storm events 
- FLash Flood
- Flood
- Hail 
- Heavy Rain 
- Thunderstorm Wind 
- Tornado 
# Used tools 
## Programs
      1. Jupiter - python 
      2. Tableau  
## Methods 
      1. Logistic Regression, Random Forest, GradientBoostingClassifier 
      2. Histograms, box-whisker plots 

 ##Libraries:
       1. Normalizer 
       2. StandardScaler
       3. Confusion Matrix
       4. train_test_split
       5. OneHotEncoder
       6. numpy
       7. pandas 

# Workflow 
      1. look for dataset 
      2. gather the data 
      3. explore the data 
      4. clean the data 
            a. Drop columns 
                  i. 90% Nan's 
                  ii. Not relavent 
