# New-York-Taxi-Analysis
Data Analysis Exploration Project 

### Original Course Repo
Course Repo: 
https://github.com/misraturp/Guided-project-course-material 



### Environment Creation with Conda 
```
conda create -n newyorkanalysisenv python numpy pandas pyarrow matplotlib 

conda activate newyorkanalysisenv

conda install -c conda-forge scikit-learn jupyterlab
```

### Start Working 
```
python -m jupyter lab
```
### Data Source 
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

```
mkdir data

# https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2019-01.parquet
# https://d37ci6vzurychx.cloudfront.net/misc/taxi_zone_lookup.csv

cp <downloaded file> ./data
```
