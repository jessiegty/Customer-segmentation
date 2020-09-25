## Identify-Customer-Segments
Using RStudio to conduct PCA and clustering in population dataset and customer dataset to identify the target customers.

## Introduction
This project is to help a mail-order sales company to improve sales. The target audience of this campaign would also be the target group of our company, because they are assumed to have the highest expected return. Thus, the question is who are the target groups of our company? This project aims to help identify this group of people using the segments of the population. Research questions includes:

1. What are the different segmentations in the population?
2. What are the segmentation composition in the customer base?
3. Who are the overrepresented cohort in our company? The data comes from Bertelsmann Arvato Analytics, and represents a real-life data science task.

## Process and Purpose
There are 3 files associated with this project:

1. Population_Subset.csv: Demographics data for the general population; 891211 persons (rows) x 85 features (columns).
2. Customers_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
3. Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. You will use this information to cluster the general population into groups with similar demographic properties. Then, you will see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.
