# Zillow
This is a simple EDA of zillow data and more to see the factors that affect the house price of U.S. Market in the past 20 years.

A simple overview on Housing dataset and its multiple affecting factors.
Purchasing a home is an enormous decision during a person’s life and wishes a substantial amount of thought and research. One would really like to shop for a house at the simplest rate and minimum risk and would really like it to be the simplest investment for the longer term . Various online websites, land agents and realtors attempt to guide home buyers by letting them compare different houses available for purchase.

In this article, we are getting to discuss the results obtained for a knowledge science project for House price prediction. We try to visualise the data considering factors like Median income during a county, rate therein county, public schools, hospitals, hospital ratings and percentage within the county.

The aim of the project is to supply the simplest counties/areas within the USA to take a position certain a national land developer, individual buyers, banks trying to find an area to develop a replacement apartment house or to get . Another goal is to predict the house prices during a county within the next few months.

What is the anticipated price per sq ft of a range in a given zip code/ county within the next few months? Can we predict the worth supported crime rates, schools and other information/metrics provided by Zillow for a zipper code/neighborhood/county?

“Is 2020 an honest year to shop for a house?” and “Where should one buy a house?” are important questions. This House prediction project tries to answer these with the assistance of knowledge from various sources and considering factors which affect the house prices.

Stakeholders for this type of project will be:
1) Customers and land Agents — the important estate industry has long operated consistent with its own traditions, but the supply of giant volumes of knowledge is revolutionizing the way the industry works. Big data analysis techniques are creating a replacement land market during which both customers and agents are better informed than ever before.

2) Companies — like Zillow and Trulia can use this analysis to calculate an estimated value of the worth that the house might attract supported factors like local schools, crime rates, income level, hospitals etc. and choose marketing strategy.

3) Banks — It’s not just consumers who are using big data to tell their house buying and selling decisions. Banks also are drawing on vast pools of knowledge to predict the danger that a specific loan application could pose, using information about both the worth of the house and therefore the applicant’s financial situation and history. additionally , banks also are avoiding losing out on foreclosure and short sales, as big data helps them to predict the utmost sale value that the market can bear.

Based on house prices predicted one can invest in land , find a city house better fitted to their needs where they will buy a house. House buying and selling decision would become a little easier with the prediction done by this data science project.

Caution: Though this is not a production level analysis it needs further more data for finding correlation and affecting factors. Even for the depth analysis of houses it needs more data. Here those datas are not included because either they are no more on the internet or i am not reachable to those datasets.

Data Used in this Project
1) https://data.world/zillow-data/zhvi-all-homes // for the home data

2) https://bit.ly/3rQNgOg // Crime verses Population

3) https://data.world/zillow-data/increasing-values/file/Neighborhood_PctOfHomesIncreasingInValues_AllHomes.csv // Increasing home value in the neighbourhood

4) https://www.kaggle.com/carlosaguayo/usa-hospitals // USA Hospitals

5) https://www.kaggle.com/carlosaguayo/2018-unemployment-rate-by-county // Unemployment rate by County

6) https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income // List of maximum earning Per year ststes or territories

7) https://www.census.gov/newsroom/press-releases/2020/south-west-fastest-growing.html // Fastest growing cities data by population.

Challenges
1) Zillow Economics dataset — Difficulty find appropriate dataset from Zillow to figure on as no description is definitely available. Though Data dictionary is out there it doesn't specify every dataset included within the Zillow Economics dataset. No details about the varied csv files and therefore the way they're associated with one another and the details about different attributes.

2) didn't know what's FIPS, FIPS_ST, FIPS_CT and the way to relate it with counties or zip code

3) Finding appropriate datasets for various factors like Neighbourhood, schools, income levels, hospital, unemployment rating etc. After lot of searching found the datasets which might be utilized in this project.

4) Income Levels dataset has ZIP codes and no FIPS code, so I had to seek out an answer to convert ZIP codes to FIP codes. For this I had to look for a ZIPS to FIPS dataset and merge it with income level dataset. But I have not as of now so i will leave it as it is.

5) Income level dataset — Exploring and selecting appropriate attribute of median income level to use within the project

6) the way to explore these datasets to use them separately where i can not find a way to merge them in one useful dataset for prediction of house prices supported factors — Income level, rate , Schools, Hospitals, percentage etc.

Notebook
Importing important libraries
Input of the base data(Zip_Zhvi_ALLHomes)
Data Story and Exploratory Data Analysis
Crime vs Population data
Neighborhood of All Homes data
Neighborhood Of Homes Increasing In Values_AllHomes data
Hospitals data
GeoFRED Unemployment Rate by County Percent data
Web Scraping for further data
U.S. Top states and territories by income
Highest earning State or Territory
Conclusion
