# UK-Crime_Analysis

## Introduction: The Crime Analysis task and Approach taken to the problem

This study used UK Home Office street crime data to examine the effects of the lockdown on violent crime rates across the UK Leveraging Apache Spark on the cloud IaaS platform the dataset was filtered to isolate incidents classified as violent crime at an early stage. Next, overall trends in violent crime rates were examined more closely, facilitating a broader understanding of broader patterns

To further explore the impact of lockdown programs, a prediction program was used to predict the number of violent crimes before the first lockdown began. this model takes into account relevant factors such as time information, geographical location, and types of crimes. In addition, the study sought to validate local lockdowns in the Leicester region, providing a region-specific assessment of the accuracy of the model and shedding light on the local impact of COVID-19 restrictions on violence crime rates. The use of cloud-based services ensured flexibility and efficiency in dealing with large-scale street crime cases, and enabled intensive, data-driven investigations at the relationship between incarceration and violent crime rates in the UK


## Detailed Analysis and consideration of the appropriateness of the solution for the initial problem 
Here, we have employed a combination of PySpark and Pandas to conduct a comprehensive analysis of crime data. We will now examine more closely the advantages, disadvantages and limitations of the methods used in the code:

Advantages :
* Scalability with PySpark: PySpark is used to read and optimize large scale crime statistics efficiently. Its distributed computing power enables the analysis of vast data sets that do not fit in a single machine memory.
* Data cleaning and detection: The code makes good use of PySpark for data cleaning, such as handling missing values ​​and removing duplicates. Exploratory research is carried out to understand basic statistics, the distribution and prevalence of crime types.
* Predictive modeling with linear regression: The use of linear regression for predictive modeling provides a means of predicting crime rates. It allows for the exploration of possibilities and future trends in violent crime.
* Time Series Analysis: Time series analysis includes plotting monthly crime counts, rolling mean, standard deviation, and seasonal decomposition These plots provide valuable insight into temporal patterns and trends in violent crimes.
* Geographical Analysis: The Act analyzes geographical scales by exchanging data for the "Leicester area". This local analysis contributes to a deeper understanding of crime patterns in a particular area.
* Efficient data visualization: Use the Matplotlib and Seaborn libraries to create informative graphs, which help interpret and communicate analytical findings.

Disadvantages and Limitations:
* Linear regression assumptions: Linear regression assumes a linear relationship between variables, and if the relationship is nonlinear, its predictive accuracy may be limited and more sophisticated models may be needed if crime trends are to be captured it’s hard to.
* Data quality issues: The effectiveness of the investigation depends on the quality of the underlying criminal data. Incomplete or biased data can lead to incorrect information.
* Data imbalance: Crime categories in the data set have changed over the years, which may affect comparison. Seasonal variability and local omissions pose challenges to general conclusions.
* Interpretation of visualizations: Visualizations are subjective and should be interpreted with caution. Clear labeling and context are essential for accurate interpretation.


# Conclusion

The UK Street Level Crime Data research, which encompasses nearly 65 million entries from 2010, defied predictions by showing that violent crime did not significantly increase during the COVID-19 lockdowns. The dataset, although subject to changes in crime categories over the years, has remained constant since 2014. Notably, the category 'violent crime' was converted to 'violent and sexual offence' in 2013. Although there was a steady upward trend in violent crime from 2014, the pandemic-related limitations were not what was anticipated. The study highlights the need for sophisticated analysis and questions widely held beliefs about the connection between lockdowns and violent crime. Seasonal differences were observed, but the intricacy of crime dynamics was illustrated by anomalies in places like Leicester. The results emphasize how crucial it is to take into account both foreign and local variables when analyzing crime. Although there were certain drawbacks, such shifting the categories of crimes, using Apache Spark on a cloud IaaS platform turned out to be beneficial for effective data processing. As a result, the study offers insightful information on the surprising trends in violent crime that emerged during the pandemic and calls for further thorough investigation and research to fully comprehend criminal behavior in unique situations.
 
Several questions were asked to help us analyze the dataset more thoroughly. Since 2010, authorities have collected data on street crime, Although the categories of crimes changed during the year, they remained constant since 2014. However, after COVID-19 in 2020 and the subsequent introduction of the lockdown, it was observed that the crime rate started to stabilize.This fact is clearly evident in the ‘Trend’ section of our time series analysis. Statistics can also be tested with pandas, and the results show that the statistics were very stable during the lockdown. In addition, we find seasonal differences in crime, with violent crime peaking in the summer and falling in the winter. Notable exceptions to this rule include Leicester, where crime rates actually spiked in July. With the data we have analyzed it is safe to say that violent crime rates did not increase as expected during the lockdown, infact went against the general trend of annual rate increases and remained almost constant.
