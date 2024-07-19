# Applied Statistics and EDA
This project aims to provide a thorough understanding of probability distributions and their applications in real-world data analysis and Exploratory Data Analysis(EDA).


## Features
- Imputing missing values with central tendencies.
- Creating new data from the existing data for better analysis.
- Understanding probability distributions, Hypothesis testing(Z-test, Chi_Square test, T-test).
- Histogram, boxplot, heatmap, lineplot, scatterplot and pairplots for understanding significant insights in the data.

## Dataset

- Basketball_dataset(EDA) reference

![basketball](https://github.com/user-attachments/assets/fa88520a-fbce-44d0-8b73-90c197ee6e2e)


  https://www.kaggle.com/datasets/ravisankarvangala/basketballcsv


- Startup_company dataset(Hypothesis Testing) reference

  https://www.kaggle.com/datasets/piyushchaudhari04/applied-statistics

## Tools and Techniques

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scipy
- Probability distributions

## Analysis

#### Basketball Tournamnet

- By the EDA, the company can consider approaching 'Team6', 'Team8', 'Team9', 'Team11', and 'Team21' after the previously mentioned top-performing teams. These additional teams also have high win percentages and have achieved the highest positions (1 or 2), making them worthy of consideration.

- 'Team55', 'Team56', 'Team57', 'Team58', 'Team59', and 'Team60' have not performed well, as they have low win percentages and have held positions higher than 15.

#### Startup_company data 

Problem : Based on the calculated percentages, there appears to be a slight difference in the proportion of companies that are operating between winners and contestants.

**Z-test:** Since the 0.590(p_value) > 0.05(alpha) the difference is not significant and,
    	 we fail to reject the Null hypothesis.

**Chi-square test:** Since the 0.747(p_value) > 0.05(alpha) the difference is not significant and,
    	 we fail to reject the Null hypothesis.
