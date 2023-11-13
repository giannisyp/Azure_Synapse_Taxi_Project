# New York Taxi analytics with Azure Synapse

## In this project we explore the New York taxi dataset for 2020-21 around the covid pandemic and how its affected them. 

Project Architecture 

![image](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/46878783-d062-43d7-bf5d-bfb69466dbc4)

Architecture Used is the common medallion architecture. A medallion architecture is a data design pattern used to logically organize data in a lakehouse, with the goal of incrementally and progressively improving the structure and quality of data as it flows through each layer of the architecture (from Bronze ⇒ Silver ⇒ Gold layer tables). Medallion architectures are sometimes also referred to as "multi-hop" architectures.

For the computation in the project Serverless SQL Pool is used and for the storage Azure datalakes.

For orchestrations then Azure Synapse pipelines are used which are very similar to the Azure Data Factory's pipelines.

Finally a couple visualizations are made for a better understanding of the data we consumed using the powerBI intergrated in the Azure Synapse UI.

![image](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/8b4b5484-4a60-47ed-9734-0c4d2cef2f76)

![image](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/6326244b-6bbb-4989-bb22-80213229bbec)
