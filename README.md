bank Tele-Marketing Campaign Analysis 
This project presents a comprehensive analysis of a tele-marketing campaign conducted by a Portuguese bank, utilizing Exploratory Data Analysis (EDA) to understand customer characteristics and behaviors that influence term deposit subscription. The goal is to identify patterns in demographic and contact-related features and provide actionable insights to improve future marketing campaigns.



Key Objectives
To understand customer characteristics and behaviors that influence deposit subscription.

To identify patterns in demographic and contact-related features.

To provide actionable insights to improve bank marketing campaigns.

Methodology
The analysis was performed on a dataset sourced from the bank's marketing campaign, which included customer demographics and campaign interaction details.

1. Data Cleaning and Preprocessing

Duplicate Removal: 12 exact duplicated rows were identified and removed to ensure the analysis operates on a unique and reliable dataset.



Missing Value Handling: A significant challenge was the high percentage of "unknown" values in demographic (job, marital, education, etc.) and campaign columns. All "unknown" values were replaced with the mode (most frequent value) of their respective columns to preserve data integrity.



Column Renaming: Columns were renamed for clarity, including changing the target variable y to deposit.


2. Exploratory Data Analysis (EDA) and Visualization
The exploratory phase focused on uncovering initial patterns and relationships (Distribution, Relationships, Outliers, and Patterns). Key visualizations included the distribution of the target variable (deposit), success rates by job, month, day_of_week, and education, and the duration distribution for "yes" vs. "no" outcomes.


Key Insights and Findings

Campaign Rejection Rate: Most calls resulted in customers rejecting the campaigns ("no"). (The count of "no" deposits is around 35,000, while "yes" is around 4,000 ).



Job & Age Influence: The highest deposit subscription rates (Percent of yes) were among students and retired individuals. The "yes" percentage was higher in the age range of 20-30 compared to those above 60.



Customer Status: New customers responded with a "yes" more frequently than older customers.


Targeting Issue: The analysis suggested the targeted audience was often not interested, possibly because they already had loans and credits.


Marital Status: The "yes" and "no" percentages for married individuals were approximately equal, while single and divorced individuals showed a difference in percentages.

Contributors
Shimaa Alaa 

Rawan Hossam 

Abdullah Ashraf 

Abdalla Hamdi
