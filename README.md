# Mini-Project Ironhack: Banking Marketing

![logo_ironhack_blue 7](https://coursereport-s3-production.global.ssl.fastly.net/uploads/school/logo/84/original/logo-ironhack-blue.png)

<h1>Project Maintenance & Contact Details</h1>

The people contributed to this project are [Lazarus Kon](https://github.com/lazaruskon) and [Sergi Garriga](https://github.com/sergi-garriga) as part of the beginner's mini project of our Ironhack bootcamp (Cohort: Data Analysis, Part-time, July 2022-January 2023).

<h1>What are you going to see on this project?</h1>

This repo includes the two Jupyter Notebooks that we used in order to explore the data, build a basic regression model and prepare to present our findings. We also include a link to our presentation [here](https://docs.google.com/presentation/d/1iveXxdvnnQBUMF2UdwIzTBsJV4Ddp40WyL0QMy0JYiA/edit?usp=sharing).

<h1>Data Source</h1>

We found the dataset (including dictionary) [here](https://data.world/vizzup/mental-health-depression-disorder-data).

Original dataset source available [here](https://ourworldindata.org).

<h1>Description of Dataset</h1>

The dataset is about global rates of mental health and substance abuse disorders with a specific focus on depression. Our data is comprised of 6 tables 5 of which are solely focusing on depression and (potentially) explanatory variables of global depressive rates. 

<h1>Feature Description</h1>

You can find the data dictionary [here](https://data.world/vizzup/mental-health-depression-disorder-data/workspace/data-dictionary).

<h1>About our project</h1>

Project goals included:
 1. visualizing rates of depression worldwide by using key explanatory socioeconomic variables (e.g. gender, age, country, region).
 2. creating a basic predictive model that allows us to make educated guesses about which socioeconomic traits might be linked to higher rates of depression.

Although this is one of our first steps into Data Analsis, we believe that this project is valuable since it brings mental health (and especially depression) into the limelight. Additionally, it also points out the need for further investigation as well as the creation of more elaborate predictive models in regards to mental health.

<h1>Tools & Methods of Analysis</h1>

We used a variety of instruments, libraries and models to achieve the aforementioned goals. Among others we used: 
- MySQL
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Supervised learning models for regression:
  - Linear Regression

<h2>Table of Content of 'MHD-plots' Notebook</h2>

- 1. <b>Importing Data & Data Exploration</b> 
- 2. <b>Mental Health by Regions</b>
- 3. <b>Disorders by SDI index</b>
- 4. <b>Prevalence of depression by gender</b>
- 5. <b>Prevelance of depression by gender (regions)</b>
- 6. <b>Prevalence of depression by age</b>
- 7. <b>Depression and suicide</b>

<h2>Table of Content of 'Mental Health Project with Linear Regression' Notebook</h2>

- 1. <b>Importing Dependencies & Getting Data</b>
  - 1.1. Cleaning data_gender
  - 1.2. Cleaning data_age
  - 1.3 Cleaning data_general
  - 1.4 Concat dataframes
- 2. <b>Clean the merged dataset & EDA</b>
- 3. <b>Preprocessing</b>
  - 3.1. Multicollinearity
  - 3.2. Categorical Variables
  - 3.3. Outliers
  - 3.4. Encoding Categorical Variable & Normalizing Numerical Variables
  - 3.5. 3.5 Train/Test Split
- 4. <b>Modeling</b>
  - 4.1. Model Validation
- 5. <b>Feature Importance</b>
  - 5.1 Vizualization of Predictions

## Metadata

We do want to point out that we are aware that there is room for a lot of improvement. That was a mini project we worked on while taking our very first steps as Data Analysis students. You can follow up the progression of our skills through other projects available on our respective repos.
