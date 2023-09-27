# Crop Yield Analysis demo

The purpose of this project is to demonstrate how to perform a corn yield analysis with python

## Set-Up

I recommend using WSL on windows or Linux/Unix Systems as GDAL Has some serious installing problems with Windows.

Install Requirements:
- pip -r requirements.txt
- Head to https://urs.earthdata.nasa.gov/users/new create a user and password
- Change user and password in the notebook accordingly


### Prerequisites

- Install libgdal-dev: sudo apt-get install libgdal-dev
- If you have problems installing gdal with pip, use: sudo apt-get install gdal-bin python-gdal python3-gdal


### TODO
- Verify Cloud Correction / Elimination
- Model to predict based on NDVI Values
