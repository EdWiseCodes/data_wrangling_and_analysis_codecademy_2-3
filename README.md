# data_wrangling_and_analysis_codecademy_2-3
As part of the Codecademy Data Science course, I was tasked with analysing (lightly fictionalised) data from the US National Parks Service about the species within those parks. The project is intended as an opportunity to demonstrate the data wrangling and data analysis competencies developed over the course. 

The goal of my project is to answer whether certain categories of species are more likely to be granted conservation status and whether species with a conservation status are observed more or less often than species without a conservation status.

**Project Goals**

The goals of the project are to answer these two overarching questions:
- **Question 1**: Are certain categories of species more likely to have been granted a conservation status? If so, does this hold true for all of the conservation statuses?
- **Question 2**: Are species with conservation statuses observed more or less than species without conservation statuses? Does this change between national parks?

**Data**

The data provided is in two csv files: `species_info.csv` and `observations.csv`. The first csv contains information about each of the species observed and the other csv lists observations of each of those species by national park. Through data wrangling methods, I remove duplicate rows in the species csv and sum the multiple observations in the observations csv to create a usable dataframe, `new_df.csv`.

**Analysis**

In analysing the data, a mixture of descriptive statistics, data visualisation, and inferential statistics are used in an attempt to answer the two questions asked at the outset.

**Evaluation**

The project concludes by evaluating whether the questions outlined above have been answered satisfactorily.

**Please note** that the **data wrangling** takes place in the **first** of these two notebooks, and the **data analysis** takes place in the **second** of these two notebooks. 
