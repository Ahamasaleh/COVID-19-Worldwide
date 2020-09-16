# Prediction COVID-19-Worldwide Mortality rate based on Neural Networks model.

In this project real time datasets has been used to predict the mortality rate in each country and the total mortality rate worldwide including country-wide per-capita coronavirus-related mortality, based on countries' socioeconomic status including population, demographics, gross national product (GNP) per capita, gross domestic product (GDP) per capita,  political stability, urbanization, government effectiveness, hand-washing facilities, and others. For this objective, Feed Forward Neural Network (FFNN) has been used.
6 data sets are combined from different publicly available sources. The attributes that are considered in this project for predicting worldwide COVID-19 mortality for the period 1st January 2020 to 20 June 2020 are obtaind from the following data sets:

Countries of the World
From this data set a total of 227 Countries and territories information were acquired like: Population, Literacy rate,
GDP per capita, Infant mortality, Net migration, Population Density, Area (sq. mi.), Climate, Birthrate, Death rate, Agriculture, and Industry.

COVID-19 data
This data set is a collection of the COVID-19 data which is updated daily and maintained by Our World in Data, includes data on these variables; Total confirmed Cases, Total deaths, Total tests, New cases, Tests units, Stringency index, Population, Population density, Median age, People aged 65 older, People aged 70 older, GDP per capita, Extreme poverty, COVID death rate, Diabetes prevalence, Female smokers, Male smokers, Handwashing facilities, and Hospital beds per 100k for a total of 209 Countries and territories.
In order to determine the mortality rate; the number of totals confirmed cases and the number of total deaths have been extracted from this dataset by filtering the total deaths for each month starting from January 2020 until the 20th of June and combine it to the final data set as new variables.

Worldmeters corona data set
It's another source for COVID-19 data for a total of 214 Countries and territories, the information is up to the mid of May 2020 including Total confirmed Cases, Total deaths, Total tests and Serious critical cases.

Worldwide Governance Indicators
The WGI are composite governance indicators based on over 30 underlying data sources are rescaled and combined to create six aggregate indicators of dimensions of governance for over 215 countries and territories over the period 1996-2018, which are; Voice and Accountability, Political Stability and Absence of Violence, Government Effectiveness, Regulatory Quality,  Rule of Law, and Control of Corruption.
The most updated six indicators data have been selected and combined to the final data set.

Human rights data set
This data set contains quantitative information on government recognition of 15 internationally recognized human rights in more than 200 countries from 1981-2011. It includes measures of the practices of governments that allow or impede citizens who wish to exercise their physical integrity rights like the rights not to be tortured, summarily executed, disappeared, or imprisoned for political beliefs; civil liberties such as free speech, freedom of association and assembly, freedom of movement, freedom of religion, and the right to participate in the selection of government leaders; employment rights; and rights of women to equal treatment politically, economically, and socially.
This dataset has been considered to examine the human rights effects on the outbreaks, only the last updated data have been selected and combined to the final data set.

Demographic
From this data set, data for a total of 164 countries from  1960 to 2018 has been downloaded.
data about GNP per capita, Inflation rate, Industry, Life expectancy, Total Fertility Rate, Population, Migration rate, Political stability were extracted then only the last updated data have been selected and combined to the final data set.
