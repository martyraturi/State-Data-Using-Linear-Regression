# State-Data-OPTIONAL-
MITx: 15.071x The Analytics Edge




IMPORTANT NOTE: This problem is optional, and will not count towards your grade. We have created this problem to give you extra practice with the topics covered in this unit.
State Data (OPTIONAL)
We often take data for granted. However, one of the hardest parts about analyzing a problem you're interested in can be to find good data to answer the questions you want to ask. As you're learning R, though, there are many datasets that R has built in that you can take advantage of.

In this problem, we will be examining the "state" dataset, which has data from the 1970s on all fifty US states. For each state, the dataset includes the population, per capita income, illiteracy rate, murder rate, high school graduation rate, average number of frost days, area, latitude and longitude, division the state belongs to,  region the state belongs to, and two-letter abbreviation.

Load the dataset and convert it to a data frame by running the following two commands in R:

data(state)

statedata = cbind(data.frame(state.x77), state.abb, state.area, state.center,  state.division, state.name, state.region)

If you can't access the state dataset in R, here is a CSV file with the same data that you can load into R using the read.csv function: statedata.csv

After you have loaded the data into R, inspect the data set using the command: str(statedata)

This dataset has 50 observations (one for each US state) and the following 15 variables:

Population - the population estimate of the state in 1975
Income - per capita income in 1974
Illiteracy - illiteracy rates in 1970, as a percent of the population
Life.Exp - the life expectancy in years of residents of the state in 1970
Murder - the murder and non-negligent manslaughter rate per 100,000 population in 1976 
HS.Grad - percent of high-school graduates in 1970
Frost - the mean number of days with minimum temperature below freezing from 1931–1960 in the capital or a large city of the state
Area - the land area (in square miles) of the state
state.abb - a 2-letter abreviation for each state
state.area - the area of each state, in square miles
x - the longitude of the center of the state
y - the latitude of the center of the state
state.division - the division each state belongs to (New England, Middle Atlantic, South Atlantic, East South Central, West South Central, East North Central, West North Central, Mountain, or Pacific)
state.name - the full names of each state
state.region - the region each state belong to (Northeast, South, North Central, or West)
