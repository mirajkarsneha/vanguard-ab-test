# Vanguard Project

## Description
Vanguard
About Vanguard: A leading investment management company known for low-cost mutual funds, ETFs, and client-first services.
Digital Transformation Focus: Vanguard is committed to enhancing the client experience through continuous digital improvements.

### The Digital Challenge
Context: To improve user interactions, Vanguard tested a new user interface (UI) for its digital platform.
Objective: The goal was to determine if the new design would lead to higher completion rates for digital processes compared to the old design.

### Main Question
Did the new UI lead to higher completion rates?
The analysis focuses on comparing the completion rates between the new (Test) and old (Control) designs to evaluate the effectiveness of the changes.

### KPI 1: Completion Rate: The proportion of users who reach the final ‘confirm’ step

### KPI 2 : Time Spent on Each Step

### KPI 3 : Error Rates

## Hypothesis 1 : Completion Rate
#### H0: There is no significant difference in the completion rates between the Test and Control groups.
#### H1: The completion rate for the Test group is significantly higher than that of the Control group.

## Hypothesis 2 : Completion Rate with a Cost-Effectiveness Threshold
#### H0: The new UI design meets the cost-effectiveness threshold.
#### H1: The new UI design does NOT meet the cost-effectiveness threshold.

## Hypothesis 4: The average client tenure
#### H0: The average client tenure of those engaging with the new process is equal to the average tenure of those engaging with the old process.
#### H1: The average client tenure of those engaging with the new process is not equal to the average tenure of those engaging with the old process.

## Prerequisites
- Python Project
- Tableau
- Jupiter notebook
- Git Hub link- https://github.com/mirajkarsneha/cinematic-insights
- Notion link- https://www.notion.so/Project-2-Vanguard-12092ac0a14e806c8567e636a54bb2ce
- Presentation link - https://docs.google.com/presentation/d/1uMW45RJiZBBCC8guZ9g5GpOMTubpT_Pn/edit#slide=id.p11

## Data Cleaning and Merging
- Removed duplicates and irrelevant columns.
- Handled missing values by applying imputation strategies or filtering out incomplete records.
- Standardized date formats and ensured consistency across datasets.
- Merged Client Profiles and Digital Footprints using visitor_id to link user interactions with demographic data.
- Combined the merged dataset with the Experiment Roster based on visitor_id to assign group labels and experiment details.
- The integrated dataset allows analysis of user behavior and completion rates for both Test and Control groups.

## Project Structure
This is a python project has below mentioned files.
- kpis.ipnyb - kpis file is the main file which has all the logic written for the kpis and hypothesis-
- README.md - Describes what the project is, how it is structured and what changes are applied to get a clean data file.
- data_cleaning.ipynb - How the data is being cleand based on the kpis & Hypothesis logic
