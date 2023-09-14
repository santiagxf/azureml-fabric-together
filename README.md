# Azure Machine Learning and Fabric

This repo contains two examples about how you can use Azure Machine Learning and Fabric together.

## Example 1
### Read data from OneLake and create data assets to reference it

This demo shows how you can use `mltable` assets in Azure Machine Learning to read delta-formatted data in OneLake. Use time-travel feature to ensure reproducibility of the results. This demo is intented to be executed in Azure Machine Learning. [Link to example](examples/azureml-read-delta-assets.ipynb).

## Example 2
### Consume predictions from models deployed in Azure Machine Learning Online Endpoints

This demo shows you can use MLflow deployment client to connect to Azure Machine Learning and invoke endpoints to generate predictions. Models are hosted in Azure Machine Learning Online Endpoints where they can be consumed for multiple workloads. This demo is intended to be executed in Fabric. [Link to example](examples/fabric-consume-azureml-endpoints.ipynb).

## Example 3
### Consume predictions from models deployed in Azure Machine Learning Batch Endpoints

This demo shows you can use Batch Endpoints to produce predictions of models or complete pipelines and store the predictions in Fabric OneLake. Models are hosted in Azure Machine Learning Batch Endpoints where they can invoked and consumed from multiple workloads using a durable API. This demo is intended to be executed in Fabric. **[Soon]**

## Notice

These examples don't represent all the ways users may combine the two products, nor a recommendation about how to do it. It is shared only as a quick start for users working with Azure Machine Learning and Fabric, highlighting some of the existing features they can use.
