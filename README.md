# Storm_type_final_project 
![photo]()

Data sets were taken from the following link: https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/
# Objective/Question 
Develop a classification machine learning model to predict EVENT_TYPE using the dataset taken from national centers for environmental information(NOAA). The dataset has information about 
      - when the event happened:duration, month, year, time
      - where it happened:i.e. state, county
      - damage caused by the event:i.e. deaths, cost of damage to both crops and property, injuries.       
 Most recent years were selected, 8 in total providing over 400,000 data points for the united states. 

 # How to tackle it 
 In this repo you will find 4 ipynb files, begin with Explor_data.ipynb which takes an initial look a the data set and what possible trends or varibales may hold interest. Then follows Gather_compress_files, which selects the years with functioning files i.e location,details and fatalites for that year. They are then merged into one larger file for cleaning. Cleaning then identifies columns with repeating information, removes nans, outliers, and unecessary columns for the model. Classification_model_old scales the data for use in the following models: logisitical regression, random forests, and XG boost. While comparing model accruacy differences between SMOTE (oversampling)and TomekLinks(undersampling).  
 
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

## Libraries:
       1. Normalizer 
       2. StandardScaler
       3. Confusion Matrix
       4. train_test_split
       5. OneHotEncoder
       6. numpy
       7. pandas 

## Workflow 
      1. look for dataset 
      2. gather the data 
      3. explore the data 
      4. clean the data 
            a. Drop columns 
                  i. 90% Nan's 
                  ii. Not relavent 
                  iii. Repeated information
            b. Lower column heads 
            c. Fill Nan's with median 
            d. Check dtypes 
            e. Correlation Matrix 
            f. Check categorical data 
                  i. if value count is more than 100 drop or clean 
            g.outliers/boxplots 
            h.Save new data set in a new csv  
       5.Classification model 
  
 # Next Time 
 Other project ideas could have been to take a closer look at specific states and identify overall trends. While ignoring the location file all together to get a more consecutive time line.
      
