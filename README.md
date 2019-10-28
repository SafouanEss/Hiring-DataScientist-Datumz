# Data Analysis Task

The following task description and related Data sample is intended to candidates applying for a Data Scientist position within [BI & Data Science team] 'Datumz' at Avito.

## Background

The task topic aims to give more context on the *Engagement Segments Initiative*, which has been launched to evaluate how good are we performing on engaging our users.
This data-driven initiative is meant to provide us with valuable insights on how engaged our users are, and allows our product teams to promote actions to retain them more and better.


## Task

In order to capture a better value, you have to consider the following variables (Leads | Ad views | Ad Insertions).

=> *Leads* : Total number of potential users trying to contact our sellers mainly via 3 mediums ( SMS,Chat,Call) to buy any product via AVito.The lead id should be known.

=> *Ad views* : Total number of detail views performed by our visitors on any ad.The event type is tagged as 'View'

=> *Ad Inserts* : Total number of ads that any seller is posting on our platform.The event type is tagged as 'Create'

A snapshot of your sample will be presented at the bottom of the material. 


We can define **the most valuable users** as follow : 

The users above 75% percentile of total users but only taking in consideration leads and ad inserts actions. 

You have to create a **reproducible report**\* answering the following questions:

------------------------------------------------------------------------------------------------------------------------------

1. What is the share of the most valuable users in your group?
2. What are the top action the former group performs (ad inserts or leads) ?
3. Visualize the relationship between the leads events and ad inserts value across your users base ? 
4. Is there any correlation between the former actions ? 
5. Summarize your insights in an *executive summary*.
------------------------------------------------------------------------------------------------------------------------------
\* Given dependencies and other instructions, we should be able to re-run your source code with the dataset in the same directory and obtain the same results and figures. Popular formats for this include RMarkdown and Jupyter Notebook (formerly IPython).

**Note**:  you need to submit your report as a Jupyter/IPython notebook , please make sure not to upload a public copy to GitHub.

## Data Sample Description 

The dataset is built based on the behavioral actions of AVITO users during Oct 19 on AndroidApp. 

| Column          | Value   | Description                                                                       |
|:----------------|:--------|:----------------------------------------------------------------------------------|
|event_id | '013bf25f-cb1a-4c98-95d4-c0db3c6c0d83' | action identifier (string)|  
|event_type | 'View' | action type (string)|  
|event_date | 2019-10-10T04:39:44+00:00| action timestamp (string)| 
|environment_id | 'sdrn:schibsted:environment:1a6bacf7-26b9-4ca6-915d-9ba3a6a40dbc'| user device identifier (string)|
|ad_id | 'sdrn:avitoma:classified:37306376'| advertisement identifier (string)|
|lead_id | '005f6ee8-1981-421f-a194-d9265c1ce5b0'| lead identifier (string)|
|product_type | 'AndroidApp'| event platform (string)|



* The following are possible values for event_type column : 'View','Call','Send','SMS','Create'





