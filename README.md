# New York Taxi analytics with Azure Synapse

![photo1](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/9071c415-f200-4606-a4cc-ab1b8f067311)


## In this project we explore the New York taxi dataset for 2020-21 around the covid pandemic and how its affected them. 

Project Architecture 

![photo2](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/652e981e-aade-4468-9d88-f438cf05c7ae)


Architecture Used is the common medallion architecture. A medallion architecture is a data design pattern used to logically organize data in a lakehouse, with the goal of incrementally and progressively improving the structure and quality of data as it flows through each layer of the architecture (from Bronze ⇒ Silver ⇒ Gold layer tables). Medallion architectures are sometimes also referred to as "multi-hop" architectures.

For the computation in the project **Serverless SQL Pool** is used and for the storage Azure **datalake**.

For orchestrations then **Azure Synapse pipelines** are used which are very similar to the **Azure Data Factory's pipelines**.

Finally a couple visualizations are made for a better understanding of the data we consumed using the powerBI intergrated in the Azure Synapse UI.

![photo3](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/d67ade3b-da3b-4678-bdfd-89ac1fd3878b)

![photo4](https://github.com/giannisyp/Azure_Synapse_Taxi_Project/assets/119696474/2598048d-c9d4-4d74-8bd8-5712011aa2cb)


Later on the project Azure synapse Link is used to move the data from the sql db to the data warehouse.
