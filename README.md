# USDA Organic Program Enforcement Analysis 

This repository contains data obtained by the [Data Liberation Project](https://www.data-liberation-project.org/), via a [Freedom of Information Act request] (https://www.data-liberation-project.org/datasets/usda-organic-program-enforcement/) to the US Department of Agriculture’s National Organic Program and pre-processed by the Data Liberation Project. 

## FOIA Records

The records provided by the US Department of Agriculture’s National Organic Program can be viewed [HERE](https://docs.google.com/spreadsheets/d/1gHNKxVObWfm1Q1JzkhDl8Wx4wKIPU-Wp/edit?gid=1251061210#gid=1251061210).


## Code 

This repository contains one Malloy code file: :

- [`US_Organic_Program_Enforcement.malloynb`](US_Organic_Program_Enforcement.malloynb), performs the analysis of the data provided by the Data Liberation Project. 


## Description of Project
Per the Data Liberation Project website, "The US Department of Agriculture's National Organic Program launched the COMPLIANCE Database...The tool allows the organization to better track case progress and more quickly identify patterns and relationships across complaints."

This project discusses different trends across the origins of investigations and outcomes. Ultimately, we utilize Malloy to understand the US Department of Agriculture's Compliance Database. Once analysts understand the database, we evaluate year-over-year trends and the overall effectiveness of the US Agriculture Department's investigative team so that decision-makers can be better informed about this organization.

## Motivation 

Within agriculture, there is always a looming pressure to perform well. With the added pressure comes the risk of fraud and other misconduct among those in the agricultural sphere. According to the United States Department of Agriculture website, the department has been a part of many intense and intricate investigations that you can read more about [HERE](https://www.rma.usda.gov/about-rma/department-justice-prosecutions). The purpose of this analysis was to find trends in the different investigations that had occurred under this United States Department's purview. 

## Data cleaning steps
Although the data was relatively clean, a few data-cleaning steps needed to occur for the program to run the code; for example, the Date/Time Open and Closed columns had to be converted to a better format for users. The collected amount column displayed civil penalties that needed commas and dollar signs to be recognized. However, Malloy could not read the dollar signs and commas, so new dimensions were required to fix this issue. Days and years in the dataset also needed extra dimensions for higher-level analysis. 

## Summary of Findings

Much like deep sea divers uncovering lost treasure in the ocean, as analysts, we also must discover the truth hiding beneath the waves of a sea of data. While going through this dataset, we will uncover some interesting findings that help us understand the bigger picture of what is happening in US agriculture. 

While going through the data, we will find that some organizations have a propensity for repeated investigations of illegal agricultural practices.

We will also find that specific civil cases result in fines ranging from a few hundred to several thousand dollars.

The target of the analysis will ultimately be to discover if the US Department of Agriculture has been having an acceptable amount of fraud discovered or if decision-makers at the government level need to re-evaluate the effectiveness of this organization's investigatory skills. 

Please see the table below for a sample of screenshots of visualizations that will be shown in the analysis: 
| **Examples**   | **Image Preview** |
|--------|-----------|
| `Organization Investigated Repeatedly` | <img src="USDA_Organic_Program_Enforcement_Organization_Investigated_Repeatedly.png" width="100%"> |
| `Complaint Versus Multiple Outcome Correlation` | <img src="USDA_Organic_Program_Enforcement_Complaint_Versus_Multiple_Outcome_Correlation.png" width="50%"> |
| `Negative Outcomes Over the Five Year Range` | <img src="USDA_Organic_Program_Enforcement_Negative_Outcomes_Over_Five_Year_Range.png" width="50%"> |
| `Case Length Versus Punishment Correlation` | <img src="USDA_Organic_Program_Enforcement_Case_Length_Versus_Punishment_Correlation.png" width="50%"> |
| `Government Department Effectiveness` | <img src="USDA_Organic_Program_Enforcement_Governement_Department_Effectiveness.png" width="50%"> |

## Description of how others can build off of this work

Others can build off this work in various ways. Data analysts could use the trends in this project to forecast estimated future cases for the US Department of Agriculture. Decision makers at a government level could use the information to improve the effectiveness of this US Department. Finally, the general public could build off this work by applying more measures and dimensions to clarify understanding of the compliance dataset. 

## Directions on how to use the github web editor to run the same analysis

Are you logged into github? Just press the period key right now. This will load the web editor. Then install the malloy extension. See images below for reference:
| **Step**   | **Image Preview** |
|--------|-----------|
| `Step 1 - Press allow` | <img src="step1.png" width="50%"> |
| `Step 2 - Click the Blocks, search for Malloy, install` | <img src="step2.png" width="50%"> |
| `Step 3 - Click Trust` | <img src="step3.png" width="50%"> |
| `Step 4 - Click a .malloynb file` | <img src="step4.png" width="50%"> |
| `Step 5 - Press Run` | <img src="step5.png" width="50%"> |

## Licensing

The files provided directly via FOIA (see listing above) are, as government documents, now in the public domain. All other data files have been generated by Josh Hyer for Gonzaga University Graduate School of Business as part of the MSBA-622-01 Data Science for Business (Spring 2025) course and are available under Creative Commons’ [CC BY-SA 4.0 license terms](https://creativecommons.org/licenses/by-sa/4.0/). This repository’s code is available under the [MIT License terms](https://opensource.org/license/mit/). 
