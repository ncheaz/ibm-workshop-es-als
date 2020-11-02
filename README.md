# Collaborative Filtering with Watson Studio and Elasticsearch on IBM Cloud

This code pattern walks you through the process of setting up a Watson Studio stack on IBM Cloud that can run through a sample Jupyter Notebook that trains publicily available data sets for Collbaroative Filtering on Elasticsearch.


## Pre requisites

- Have an IBM Cloud account

- It's possible to use IBM Cloud free tier to follow this code pattern, but need to have a internet accessible instance of Elasticsearch

- Working knowledge
    
    - Elasticsearch

    - Python

    - Jupyter Notebooks

## Outline  
  

### Setup Watson Studio Instance
- Log into IBM Cloud account
- ...
- It takes 10 minutes to stand up the instance

### Setup Elasticsearch Instance
- Create Elasticsearch ICD instance
- ...
- It takes 10 minutes to stand up the instance

### Setup Elasticsearach Hadoop connector for Watson Studio
- Go to the watson studio data sources, select Elasticsearch as one of the options

### Load the samle Jupyter notebook for collborative filtering
- Go to Watson Studio
- Upload notebook
- Select the file `elasticsearch-spark-recommender.ipynb`

### Run the notebook
- Update the notebook to point to your instance of Elasticsearch
- Run the notebook
- Get recommendations
- Change some parameters
- Try out the changes

