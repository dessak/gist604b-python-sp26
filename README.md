# Python, Dataframe, and Containerization Introduction
**Student:** Dessa Keys  
**Course:** 604B — Open Source GIS  
**Module:** 3 Python GIS and Containerization  
**University of Arizona**

## Project Description
This project introduces containerization using Docker. It also introduced dataframes as well as spatial dataframes using GeoPandas and analysis for vector data and Rasterio for raster data.

## Tools and Technologies
- Docker  
- Pandas  
- Geopandas  
- Rasterio  
- Jupyter Notebook  

## What I did
- Launch containerized environment using Docker  
- Process non spatial data with Pandas  
- Process vectorized spatial data with Geopandas  
- Process raster data with Rasterio  
- Create processing python scripts  

## How to View / Run
Initial Processing steps can be viewed in the Jupyter Notebook in the [notebooks folder](https://github.com/dessak/gist604b-python-sp26/tree/main/notebooks). Python scripts can be run within containerized Python environment.

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   ├── Dockerfile
    ├── data/
    │   ├── neighborhood_samples.geojson
    │   ├── temperature_readings.csv
    │   └── weather_stations.csv
    ├── notebooks/
    │   ├── pandas/
    │   ├── geopandas/
    │   └── rasterio/
    ├── src/
    │   ├── pandas_basics.py
    │   ├── geopandas_basics.py
    │   └── download_real_data.py
    ├── tests/
    │   ├── test_pandas_basics.py
    │   └── test_geopandas_basics.py
    ├── pyproject.toml
    └── uv.lock
