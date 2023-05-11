# Covid Mitigation Data Engineering and Analysis

## Project Description

To advise the fictional country of Caladan on COVID policy, this project analyzed COVID-19 data from 10 countries to determine the most effective COVID-19 policies with the least restrictive effects. We placed a focus on two contrasting countries: Sweden, which had relatively relaxed COVID policies; and New Zealand, which had some of the strictest policies in the world. We concluded that restrictions on workplace closing, gathering restrictions, and facial coverings proved to be the most effective while also being the most permissible. We recommend that Caladan take a timely, dynamic, and targeted response to COVID mitigation.

## Supplementary Materials

* [Report](Report.pdf)
* [Power BI file](covid19.pbix)
* [Presentation](DS310_Presentation.pdf)
* [Azure Data Factory Branch](https://github.com/lavaman131/covid-mitigation-analysis/tree/adf_publish)
* [Azure Synapse Branch](https://github.com/lavaman131/covid-mitigation-analysis/tree/synapse_publish)
* [Resource Group ARM Template](ARM_template.zip)


## Data Engineering Concepts
* We followed the Kimball method for our data warehousing procedure with a snowflake schema:

![](imgs/schema.svg)

* Here is an overview of our ELT pipeline:

![](imgs/ELT_pipeline.svg)

## Technology Stack

This project was implemented using the following technology stack:
* Azure's cloud platform
* Azure Data Factory
* Azure Data Flows
* Cosmos DB
* Azure SQL