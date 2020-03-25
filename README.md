**FOOTBALL ANALYSIS**

This repo contains jupyter notebook in which codes were written to analyse FIFA rankings for numerous footballers. The data that was analysed is contained in a csv file title "WorldCupMatches". The analysis generates a model that predicts the values of footballers based on some personal details of the footballers. Charts and plots were also made to show relationship between the value of players and basic information about the players. One very notable observation from the data is that the value of players automatocally becomes their release clause(amount of money their current club will sell them). By using the model managers of football clubs can predict the value of the players and plan on the release clause before hand if they want to by the player by the end of the season.

**PROCESS OF ANALYSIS**

1.**_First off the data was cleaned_**

This entailed changing some columns that were objects to "floats" and "int". Python programming language understands basic characters to be either strings, floats and ints. strings are the alphabets while floats and ints are numbers. That a datatype appears to be a number in python doesn't necessarily means that python recognises it as a number. So it was discovered that some data which appeared to be ints were recognised as strings by python and so, they needed to be converted to ints.
The data is in form of tables and the tables have some columns that the values are  missing. In order to increase the accuracy of the model the missing values have to be inputed. They were inputed using some data wrangling techniques seen in the code.

2.**_Data Analysis and Visualisation_**

trends were discovered in the data and visualised using charts and plots(each chart is explained in the notebook)
questiones were raised and answers were inferred from the data. some of the questions derived were: "how does the ages of players affect their value?", "At what age will it be economical for a manager to buy a player" Etc.

3.**_Predictive Modelling_**

The data was trained using RANDOM FOREST REGRESSOR and the accuracy was not so good. It was presumed that the level of accuracy was due to not enough essential data(columns) for the players.

**INSTALLATION**

The packages need to install the tool used is contained in the REQUIREMENT.TXT file. Although an easy way to go about it is to install ANACONDA distribution.


**THANK YOU**
