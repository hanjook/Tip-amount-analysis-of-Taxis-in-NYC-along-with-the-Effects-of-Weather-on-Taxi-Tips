# Dependencies
- Language: _i.e Python 3.8.3 and/or R 4.05_
- Packages / Libraries: _i.e pandas, pyspark, sklearn, statsmodels, folium, etc... 
- External packages in: `requirements.txt`_

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
    - 2019 Jan: https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2019-01.csv
    - 2019 Apr: https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2019-04.csv
    - 2019 Jul: https://nyc-tlc.s3.amazonaws.com/trip+data/yellow_tripdata_2019-07.csv
    - 2019 Oct: https://nyc-tlc.s3.amazonaws.com/trip+data/yellow_tripdata_2019-10.csv
    
    - 2020 Jan: https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2020-01.csv
    - 2020 Apr: https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2020-04.csv
    - 2020 Jul: https://nyc-tlc.s3.amazonaws.com/trip+data/yellow_tripdata_2020-07.csv
    - 2020 Oct: https://nyc-tlc.s3.amazonaws.com/trip+data/yellow_tripdata_2020-10.csv
- Weather Dataset: https://w2.weather.gov/climate/xmacis.php?wfo=okx
    - Choose NY-Central Park Area
    - Choose the months chosen above in the TLC data.
    - Click view
    - Copy the data into excel file and save as csv.
    - Is provided in raw_data/weather

# Directory

- `raw_data`: Contains all the raw data files. The large files were not pushed, hence must be manually downloaded from the above into ../raw_data/large
- `preprocessed_data`: Contains all the preprocessed data files. These files will be automatically generated using the code
- `plots`: Contains plots and figures that were used for analysis
- `code`:
    1. "Feather Documents generator.ipynb" for "Generating feather files for taxi data of each year"
    2. "Data Processing and Feature Engineering- 2019.ipynb" for "Preprocessing","Feature Engineering" 
                                                                    ,"Merging with Weather Data" and "Preliminary Analysis of 
                                                                    features".
    3. "Data Preprocessing and Feature Engineering- 2020.ipynb" for "Preprocessing","Feature Engineering" 
                                                                    ,"Merging with Weather Data" and "Preliminary Analysis of 
                                                                    features".
    4. "Descriptive Statistics.ipynb" for "Analysing the relationships between the variables of interest with tip amounts"
    5. "Geospatial visualisation.ipynb" for "Visualising Taxi trips and analysing them"
    6. "Machine Learning.ipynb" for "Feature Selection" and "Model Selection" and "Prediction" and "Model Evaluation"
    - THE FILES MUST BE PROCESSED IN THIS ORDER!!!
- `taxi_zones`: Contains the taxi zones corresponding to the PULocations that are to be used in the code
                - Acquired from Lab 2 (in references)

# Other

****IMPORTANT**** 
MANUALLY DOWNLOAD THE TLC FILES
- The Links are above
- However, the weather Dataset will be pushed.


