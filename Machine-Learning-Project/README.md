# Machine Learning Project: Recommending Mobile Plans for Megaline

**Project Overview**:  
In this project, I developed a machine learning model to recommend one of Megaline's newer mobile plans (Smart or Ultra) based on subscriber behavior data. The objective was to achieve the highest possible accuracy, with a target threshold of 0.75.

**Links**:  
- [Machine Learning Project Notebook](./Machine%20Learning%20Project.ipynb)

## Project Description:

### 1. Data Description
- **Dataset**: `users_behavior.csv` contains monthly behavior data for subscribers, including:
  - `calls`: Number of calls.
  - `minutes`: Total call duration in minutes.
  - `messages`: Number of text messages.
  - `mb_used`: Internet traffic used in MB.
  - `is_ultra`: Indicates the plan for the current month (Ultra - 1, Smart - 0).

### 2. Model Development
- **Task**:
  - Split the dataset into training, validation, and test sets.
  - Investigated the performance of different models by tuning hyperparameters.
  - Evaluated model accuracy using the test set to ensure it met the 0.75 threshold.

### 3. Conclusion and Findings
- **Outcome**: Achieved a model with the highest possible accuracy, providing insights into which features most strongly predict a subscriber's likelihood to switch to the Ultra plan.

*This project was completed as part of the Machine Learning module in my Data Analytics course.*
