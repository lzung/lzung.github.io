---
layout: post
title: "Exploratory Analysis on Women in Data Science (2022)"
subtitle: "Extracting insights on the state of the data industry, with aims to highlight areas for improvement and encourage women to join the movement"
image: "/images/wids/education_level.png"
---
## Code Repository
- [Github](https://github.com/lzung/wids-2022)
- [Medium](https://medium.com/@laurenzung/women-in-data-science-what-representation-looks-like-in-2023-d5979158ca99)

## Technique Overview
- Python
    - altair
    - pandas
    - matplotlib
- Statistics
- Data Visualization (Interactive)

## Methods
The data set and source code that was used in the creation of this article can be found on [this Github repository](https://github.com/lzung/wids-2022). Specifically, the visualizations (along with other iterations that didn't make the cut) can be found in [this Jupyter Notebook](https://github.com/lzung/wids-2022/blob/main/src/data_cleaning.ipynb). All plots were configured using the declarative visualization library, [Altair](https://altair-viz.github.io/).  

Each figure also includes interactive components that display the exact counts and proportions, which can be viewed by clicking on the links listed in the captions.

## What is Kaggle and what is the Machine Learning and Data Science Survey?
Kaggle is an online platform that allows data enthusiasts to come together as a community and solve real world challenges. It provides users with a virtual cloud environment to train and test models, features a wide repository of datasets, hosts competitions across multiple domains, and can serve as an excellent resource for those interested in furthering their data science education.  

Since 2017, Kaggle has released an annual industry-wide survey to collect information about the state of data science. Their goal is to construct a comprehensive view of the industry from data points such as what technologies are being used, what roles have been filled, and which methods are commonly applied. This data is collected and compared year-to-year in efforts to assess ongoing trends in data science.  

While the team at Kaggle has performed their own EDA, this does not capture differences between men and women as distinct groups. Hence, I will be expanding on their work by examining survey results through the lens of gender.

## Survey Demographics

![Age Distribution](/images/wids/age_dist.png)
{:.image-caption}
*Figure 1: Age distributions for men vs. women and a donut chart representing the gender diversity of respondents. "Percentage of Respondents" is with respect to each gender.*

In Figure 1, we see that less than 23% of survey respondents identified as a member of a gender minority and only 22.0% identified as women. There also seems to be larger proportion of young women between the ages of 18 and 24 on Kaggle compared to men in the same age range. From first glance alone, it is obvious that women are a minority in the community.  

*Disclaimer: for the sake of comparison, I have chosen to exclude surveyors who did not identify as either men or women beyond this point due to the low sample sizes shown above. I support that all gender minorities deserve to be represented in tech, though I have not visualized others here to avoid any figures being misconstrued.*