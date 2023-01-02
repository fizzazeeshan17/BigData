# BigData

Download the dataset from here:

https://www.kaggle.com/datasets/dilwong/flightprices

The dataset is taken from Kaggle.This dataset is a CSV file where each row is a purchasable ticket found on Expedia between 2022-04-16 and 2022-10-05, to/from the following airports: ATL, DFW, DEN, ORD, LAX, CLT, MIA, JFK, EWR, SFO, DTW, BOS, PHL, LGA, IAD, OAK.

Compressed versions of the data (CSV in 7zip, Apache Parquet) can be downloaded here: https://github.com/dilwong/FlightPrices


Add data to Hadoop:

hdfs dfs -mkdir /target input folder
hdfs dfs -copyFromLocal “filepath”  “target input folder”

Security:

https://www.geeksforgeeks.org/hadoop-file-permission-and-aclaccess-control-list/

