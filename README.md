# Applied Research Project with Velador Associates on London Real Estate Data
## Task 1
1. Cleaning data (ALL)

2. Exploratory Data Analysis (1. Peerawat Suaysom, 2. David Simunek, 3. Tuan Nguyen)

3. Clustering of non-commercial London Real Estate Data in different dimensions (price, geographic, proximity to tube stations that are split as given by the London Fare Zones) (1. Peerawat Suaysom, 2. David Simunek, 3. Site Lei)

4. Identify supplementary data like Ofsted Classification (school ranking), Council Data (level of average benefits paid in the area) etc; (1. Dylan Nguyen, 2. Site Lei)

5. Identify new fast growing development areas such as Battersea, Aldgate etc. (1. Dylan Nguyen, 2. Tuan Nguyen)
## Meeting 0
The Real Estate Data were web-scrapped from Rightmove and you don’t need to do any data gathering, which is good news. For those that would like to learn more about this process, please read

https://github.com/toby-p/rightmove_webscraper.py

The data you have was put together with Simone and two other data scientists that work on a big real estate project that is ran in parallel, though the objectives are quite different.

Now, about the data that you will work on. I attached the outputs of Rightmove that include:

1. Private residential Real Estate data mainly in London and Oxford, though some attempts of gathering data from other cities are included, but are not relevant
2. Commercial Real Estate data only from the London area

The data contain essential information, including:
 - Full postcode of each property
 - Whether has garden (True/False)
 - Whether has balcony
 - Whether is penthouse

The data are collected for the last three weeks from April. The data from each week is split in 33 postal code regions, which explains why we have 33 Excel files for each week. Moreover, week 2 is an update of week 1 and includes many properties from week 1 without any updated details (i.e. duplicates), those from week 1 with some updated details, and inevitably, new properties that were not advertised in week 1. The same apples for week 3 data as compared to week 2. I hope these make sense.

Since we have the postal code, you should expand the dataset by using open data on school location, crimes, political-orientation, and so on so forth. This is an immediate task that you should think before the Wednesday’s meeting.
