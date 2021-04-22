[Assignment#11.pdf](https://github.com/MarianneDoane/Personal-Dataset-Project/files/6354694/Assignment.11.pdf)
# Personal-Dataset-Project
**Name:** Marianne Elizabeth Doane
**Personal Dataset Project on LGBTQ+ Hate Crime**

**Motivating Question:**
How many police-reported hate crime in Canada was LGBTQ+ (Sexual Orientation) motivated? This question is significant to me because I am the L in LGBTQ and I have experienced hate crime myself. Therefore, I thought it would be interesting to analyze the statistics that Canada has to offer on police-reported hate crime on members of the LGBTQ+ community so that 1). I would not feel alone in the struggle for equal rights, and 2). to bring awareness to how minority groups are treated.

**Data Source:** 
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3510006601&cubeTimeFrame.startYear=2012&cubeTimeFrame.endYear=2019&referencePeriods=20120101%2C20190101 This website is where the official Canadian census data is reported.
I chose Statistics Canada because they are a reliable source that has current data (2012 to 2019). The question I was asking was "How many police-reported hate crime in Canada was LGBTQ+ motivated?" I wish I could compare this data to the U.S. but unfortunately we haven't researched it enough (probably because there is less acceptance here and therefore less reason for the U.S. to go to the trouble to see if the LGBTQ+ community is being targeted for hate crime). I am therefore going to look at the difference between the individual years and see if there is a trend between the data on sexual orientation being the type of motivation listed on police-reported hate crime. I will also show the other types of hate crime motivations compared to the 'sexual orientation' column.

This is what the origional dataset looked like:
![image](https://user-images.githubusercontent.com/79335960/115638228-d377cc00-a2c6-11eb-8b74-0b06d79c9649.png)
One of the footnotes attached to the dataset from Statistics Canada had the following information about the different territories the data was retrieved from: "Includes data from municipal and provincial police services as well as the Royal Canadian Mounted Police (RCMP) covering 99.7% of the Canadian population. Coverage for each province/territory is as follows: Newfoundland and Labrador (100%), Prince Edward Island (100%), Nova Scotia (100%), New Brunswick (100%), Quebec (99.3%), Ontario (99.6 %), Manitoba (99.8%), Saskatchewan (98.8%), Alberta (100%), British Columbia (100%), Yukon (100%), Northwest Territories (100%) and Nunavut (100%).These percentages are based on 2019 populations."

**Data Process:** 
The processing steps I applied to the data was deleting rows 2012 and 2013 as there is no statistical information in these rows (therefore, I will only be working with years 2014-2019). I also made sure that the totals made sense. I did this by summing each individual row to make sure that it matched the row "Total plice-reported hate crime". I found no error; they all summed correctly.

barplots for every year (2014-2019) that express the different types of motivation for hate crime:
![image](https://user-images.githubusercontent.com/79335960/113455223-ecbfe380-93be-11eb-887b-c3826ce6e66f.png)
![image](https://user-images.githubusercontent.com/79335960/113455254-0103e080-93bf-11eb-8328-44c79a23e1c7.png)
![image](https://user-images.githubusercontent.com/79335960/113455277-10832980-93bf-11eb-99b5-0825b5f02fcb.png)
![image](https://user-images.githubusercontent.com/79335960/113455287-1973fb00-93bf-11eb-87fd-cde834ce41c2.png)
![image](https://user-images.githubusercontent.com/79335960/113455299-21339f80-93bf-11eb-99c1-54fc6e2ffce0.png)

A processing step that I did for the above barcharts was to use the R function coord_flip() so that all the "Types of Motivation" would be visible/readable. 

**Visualization and Analytical Technique:**
lineplot of the type of hate crime motivation as sexual orientation in each year:

![image](https://user-images.githubusercontent.com/79335960/113455376-4aecc680-93bf-11eb-8af3-e0ac8e7d28ec.png)


In order for me to find how many police-reported hate crime in Canada was LGBTQ+ (Sexual Orientation) motivated I decided to use the lineplot as a visualization tool. I learned from this technique that there has been a significant increase over the indicated years of assault based on sexual orientation. We can see a very significant positive trend in the lineplot. In the year 2014 there were 155 statements from police officers that sexual orientation was the motivation for a hate crime. The following years were also plotted for sexual orientation: 2015: 141, 2016: 176, 2017: 204, 2018: 186, and 2019: 263.

**Conclusion:**
I learned a little bit from this dataset about how sexual orientation is a growing hate crime according to police-reported statements from Statistics Canada. However, I don't believe there is adequate enough data to determine unarguably that there is actually more hate crimes being committed against members of the LGBTQ+ community. A factor that was not included in the data that could sway the results would be that there are more members of the community that are coming forward so the rate at which they are being hate crimed could be exactly the same each year increasing only because their numbers are increasing. This could be a possibility because more people are feeling confident enough to come out as being a member since there are people actively trying to make the world a less-judgmental, safe place. Same sex marriage was legalized across all of Canada in 2005. That would be two years into this collection of data.

**Code and Materials:**
In order to recreate the data analysis for the afformentioned Statistics Canada dataset you can click on the attached files which include the processing steps and R programming code. [Assignment#11.pdf](https://github.com/MarianneDoane/Personal-Dataset-Project/files/6354714/Assignment.11.pdf)
[raw data for R.xlsx](https://github.com/MarianneDoane/Personal-Dataset-Project/files/6354710/raw.data.for.R.xlsx)

