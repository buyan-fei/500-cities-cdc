# 500-cities-cdc
Public Health

---

# Data Science screening - 500 Cities

---

## Public Health

Public health is a large and expensive problem for policymakers to understand. It is important for policy makers to have the best information possible in order to provide health services and prevent future epidemics.

## Datasets
You have two datasets at your disposal for this exercise.

**Measure Definitions** - `500_cities_cdc_measures.csv` gives you more information on each of the measures that you will have access to.

**500 Cities Results** - `500_cities_cdc_data.csv` is a 500 row table providing you with the results for the different measures per city. This dataset is derived from the CDC 500 Cities Project. The data includes small area samples of residents from 500 US cities. Each column contains the percent of residents who answered a public health-related question affirmatively. The data has then been age adjusted[^1] for statistical purposes. In the dataset, the **AgeAdjPrv** suffix stands for **Age-adjusted prevalence**.

*Note*:  Self-reported data can be tricky due to many sampling issues, but it can paint an interesting picture of how healthy a given area鈥檚 population might be.

[^1]: This [2012 CDC Statistical Note](https://www.cdc.gov/nchs/data/statnt/statnt20.pdf) defines age adjustment as "the application of observed age-specific rates to a standard age distribution to eliminate differences in crude rates in populations of interest that result from differences in the populations鈥� age distributions."


## Your Mission
The policy team at the CDC has reached out to you to help them draw meaningful insights from the data they've collected. There are a few broad questions they want you to look into, but they're also interested in seeing any other patterns revealed in the course of your analysis.
### Exploration
To explore the dataset, briefly answer the following questions:

- Are there any regional health trends?
- Which are healthier, larger or smaller cities?
- If you split the data by geography, can you predict the health of neighboring cities?

### Correlation
Explore the 500 Cities dataset to help policy makers understand what **Prevention** measures may decrease bad **Health Outcomes** in the population. Feel free to focus on specific **Health Outcome(s)** of your choice.

### Clustering
Analyze similarities between cities and cluster cities with similar health patterns.
What could be the use of such a grouping of cities in the real world?


### Expectations
This take-home is an opportunity to show your technical "data" skills, but also your reporting style and your capability to convey your findings intelligibly. Your report will be read by technical and non-technical members of the team.

### Tools
You may use any of your preferred tools to explore these datasets. You should not feel restricted to using IPython or Python. However, please include all the code that you have written along the way as part of your submission.

### Confidentiality
The content of this assignment is confidential and should not be discussed outside of the System.

Good luck!


### Appendix - The CDC 500 Cities Project
If you are curious about the project at the source of the initial dataset, you can learn more about it [here](https://www.cdc.gov/500cities/about.htm).

This data was collected by Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health. 500 Cities Project Data [online]. 2016 [accessed Aug 10, 2017]. URL: https://www.cdc.gov/500cities.
