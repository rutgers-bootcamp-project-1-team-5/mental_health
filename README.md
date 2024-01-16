# mental_health
Mental health includes our emotional, psychological, and social well-being. It affects how we think, feel, and act. It also helps determine how we handle stress, relate to others, and make healthy choices. This project is to explore prevalence of different mental disorder for several countries. 
We are also exploring Disability adjusted life years for same countries as well. We have demonstrated use of BAR plot, line plot and T-test for analyzing data. 

# Data set used
Data has been acquired from Kaggle.com
Two main csv files used in data analysis are stored in Mental_health_dataset folder.


Before starting to code for plots and data analysis,  we did perform dataset cleanup:
Check for any null values. 
Check for min and max values
Find any outliers
Drop null and outliers from the dataset


Jupyter notebook follows following sequence of code:
1. Dependencies and setup- Importing modules and libraries
2. Reading Data sets/csv file
3. Plot a map to visually inspect DALY(Disability adjusted life years)for regional and country wise trend.
  Line plot for DALY as a result of mental disorder by region
  Line plot for DALY as a result of mental disorder by country
4. Create line plot for percent of population with different disorders for countries such as USA, China, Japan, Germany, Comoros, Djibouti, Guinea-Bissau, Lesotho and Suriname, 
5. Calculation of T-test for schizohprenia, Bipolar disorder, Eating disorders, Anxiety disorders, Drug use disorders, Depressive disorders, Alcohol use disorders and Disability-Adjusted Life Years for US and UK to compare the results.
6.  Checking for top increasing disorder and top decreasing disorder by the country.
7.  plotting bar graph for trends of linearly correlated disorder prevalence. Linear regression method has been used to analyze top increasing and top decreasing disorder and to plot a bar garph.
#All plots and images are saved in media folder.

  
# We have demonstarted Use of API to fetch kitten Images in the code.
url used: https://api.thecatapi.com

# Research Questions

1. Are wealthier countries mentally healthier than others?
Based on first plot of disability adjusted life years, we could say that wealthier countries has more mental disorders than other poor countries. However we see that there is one odd observation. Suriname which is considered poor country has higher disability adjusted life years than other poor countries. Other factors could also affect this studies such as wealthy countries have the money to track the number of people that seek mental health which might not even been offered in poorer countries.
So it is hard to come to conclusion regarding this without considering some other facts/data into analysis.

2. What mental disorders are most prevalent?
Most prevalent mental disorder for each countries are anxiety and Depression. 

3. T-test results to compare various disorders between US and UK:
Average suffering with Schzophrenia, eating disorder, anxiety, Drug use and Depression in the United States is higher than the United Kingdom.
The population percentage in the UK suffering from bipolar disorder and alcohol use is higher than the population percentage in the US.
The Disability-Adjusted Life Years is higher in the US than the UK.


