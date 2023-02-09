# Homicide-Project

For this data science project, I wanted to answer 2 primary questions: 
1.	Are there predictors of homicide rates that apply nationwide.
2.	What are these predictors and which ones are most significant. 
To answer these questions, I examined various factors at a county level, including population density, gun ownership rates, and poverty/income to try to create machine learning to accurately predict homicides rates between 2010-2020. Luckily, most of this data could be found online in publicly available data sources from the government. The exact data sources and the dates they refer to are listed below. 
There are, however, some important disclaimers to consider. While I wanted to look at gun ownership rates, there is a directory of gun owners in the United States. Instead, I used a well-known proxy, looking at the suicide rates via firearms (adjusting against population and total suicides). Using a proxy has some pitfalls, notably the gun ownership rates of places that have other common ways of suicide (such as bridges) would have a severely underreported value. Another important consideration is that the CDC does not freely provide data that can be used to identify private citizens. For this reason, certain low-population counties which did not have many homicides and suicides over this time period are not included in this study. Finally, while I did my best to keep the data as consistent as possible, since data is taken from several sources, the data report date is different between the sources. 
I have split the project into 3 separate notebooks: 
1.	Data Modification: pulling the data from csv files, cleaning the data and consolidating the different attributes into a single data frame.  
2.	EDA: do basic exploratory data analysis and any final data modification required before the model creation step. 
3.	Model Creation: split the data into testing and training sets, before performing the machine learning to perform feature selection and create the best possible model. 

I hope you find this project interesting and informative; my data sources are listed below (note: the csv files published in GitHub may have different file names than original pull. They also may be truncated to remove certain unused columns). 






Population Density: https://covid19.census.gov/datasets/21843f238cbb46b08615fc53e19e0daf_1/explore?location=18.286026%2C0.315550%2C2.18&showTable=true

Suicides & Homicides: 
https://wonder.cdc.gov/controller/datarequest/

Income & Poverty: 
https://www.census.gov/programs-surveys/saipe.html
