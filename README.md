# Personal-Dataset-Project
**Name:** Marianne Elizabeth Doane
**Personal Dataset Project on LGBTQ+ Hate Crime**

**Motivating Question:**
How many police-reported hate crime in Canada was LGBTQ+ (Sexual Orientation) motivated?

**Data Source:** 
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3510006601&cubeTimeFrame.startYear=2012&cubeTimeFrame.endYear=2019&referencePeriods=20120101%2C20190101
I chose Statistics Canada because they are a reliable source that has current data (2012 to 2019). The data originally comes from the Canadian census. The question I was asking was "How many police-reported hate crime in Canada was LGBTQ+ motivated?" I wish I could compare this data to the U.S. but unfortunately we haven't researched it enough (probably because there is less acceptance here and therefore less reason for the U.S. to go to the trouble to see if the LGBTQ+ community is being targeted for hate crime). I am therefore going to look at the difference between the individual years and see if there is a trend between the data on sexual orientation being the type of motivation listed on police-reported hate crime. I will also compare the other types of hate crime motivations to the 'sexual orientation' column.

**Data Process:** 
The processing steps I applied to the data was deleting rows 2012 and 2013 as there is no statistical information in these rows (therefore, I will only be working with years 2014-2019). I also made sure that the totals made sense. I did this by summing each individual row to make sure that it matched the row "Total plice-reported hate crime". I found no error; they all summed correctly.

barplots for every year (2014-2019) that express the different types of motivation for hate crime:
![image](https://user-images.githubusercontent.com/79335960/113455223-ecbfe380-93be-11eb-887b-c3826ce6e66f.png)
![image](https://user-images.githubusercontent.com/79335960/113455254-0103e080-93bf-11eb-8328-44c79a23e1c7.png)
![image](https://user-images.githubusercontent.com/79335960/113455277-10832980-93bf-11eb-99b5-0825b5f02fcb.png)
![image](https://user-images.githubusercontent.com/79335960/113455287-1973fb00-93bf-11eb-87fd-cde834ce41c2.png)
![image](https://user-images.githubusercontent.com/79335960/113455299-21339f80-93bf-11eb-99c1-54fc6e2ffce0.png)

A processing step that I did for the above barcharts was to use the R function coord_flip() so that all the "Types of Motivation" would be visible/readable. 

**Visualization:**
lineplot of the type of hate crime motivation as sexual orientation in each year:

![image](https://user-images.githubusercontent.com/79335960/113455376-4aecc680-93bf-11eb-8af3-e0ac8e7d28ec.png)


I learned from this technique for analyzing data that there has been a significant increase over the indicated years of assault based on sexual orientation.
We can see a very significant positive trend in the lineplot. 

**Analytical Technique:** 
