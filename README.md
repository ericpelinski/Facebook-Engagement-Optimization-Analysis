# Facebook-Engagement-Optimization-Analysis

## Overview
Analyzed a dataset of 500 Facebook posts from a European cosmetics brand to identify key drivers of user engagement and provide data-driven recommendations for content strategy and budget allocation.

This project was designed to be a way to develop my skills in data analysis, with an emphasis on communicating practical insights clearly and effectively. Using a real-world dataset from the UCI Machine Learning Repository about a European cosmetics brand's Facebook page, I was able to discover some practical recommendations for improving a post's Total Interactions, including the following: 
* Status and Photo posts significantly outperform Link posts in generating user interactions.
* The optimal time to post is mid-week (Wednesday) and during the months of February, May, and September.
* Paid promotion provides the most significant engagement lift for Photo posts, and is far less effective with other post types.

Lastly, I created cross-validated Linear Regression and Random Forest models to predict Total Interactions on a given post, ultimately achieving an R^2 of 0.26 on a hyperparameter-tuned RF model, a 73% improvement over the baseline RF model. The process of building these models revealed that, when taken all together, the variables "Post Hour" and "Category" were most important to predicting "Total Interactions".

### Dataset Discussion

The dataset used in this project comes from the UCI Machine Learning Repository, found [here](https://archive.ics.uci.edu/dataset/368/facebook+metrics), and was downloaded in June of 2025. The dataset contains 500 observations and 19 features. The data was collected during the calendar year 2014.

It is extremely important to note that the findings of this project are unlikely to be applicable to today's social media environment, as changes in algorithms and user content consumtion habits can shift drastically over time. The data also excludes specific creative content for each post, instead only providing metadata information. 

### Technologies and Skills Used
* **Analysis:** Python, Pandas, SciPy, Hypothesis Testing, Correlation Analysis, Data Cleaning, EDA
* **Visualization:** Matplotlib, Seaborn
* **Modeling:** Scikit-learn (Linear Regression, Random Forest)

### Conclusions and Future Research

Im quite proud of this work. It required me to learn new tools, strategies, and statistical methods to provide insights that can be trusted. Despite being limited by the dataset, achieving a R^2 of 0.26 based exclusively on a post's metadata proves that, while one can be confident that the actual content of a post plays the most substantial role, the post's type and the time it was posted do indeed play a legitimate role in improving it's total interactions. 

To build on this project, I think a dataset that includes the creative content of a post can be very interesting. Perhaps, for text-based posts, sentiment analysis and character counts could provide actionable recommendations for how a social media team could optimize engagement. Furthermore, a dataset which spans more than 1 year would allow us to determine if the seasonal patterns of engagement are consistent across years. 


