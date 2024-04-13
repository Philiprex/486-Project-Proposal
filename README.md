Margie (mt4446a@american.edu) 

Philip (pe4003a@american.edu) 

4/12/2024

Status Update

We have determined that d3 will be the best library for our visualization implementations since there are several interactive elements like a slider to give a range of years, different filtering variables for our map, and a brushing element for our parallel line plot. Although it is taking longer than expected, we are confident that it is the right decision to use d3 as opposed to vega lite. We dedicated a large amount of time to cleaning and reformatting the data into a format suitable for our needs. This reformatting included ensuring that each variable had a unique ID, which we determined is unit ID rather than OPE ID. As of now, we have not made any changes to our proposed visualizations. 

The boxplots are coming along well. We have already implemented the slider and button that allow the user to select a date range and toggle between public and private schools. Although we will return to the boxplots to finalize the aesthetics and create a smooth interface, we are shifting our focus to the map and the parallel line plot. We hit a roadblock with the parallel line plot with the structure of the data. However, we believe that we have found a way to pivot the data to suit our needs. Moving forward, we are hoping to have the rough visualizations completed mid-next week (~4/17/24). We will then begin the revision process.

Here is a link to our observable project thus far: https://observablehq.com/d/c0c95c020e5e6e70


03/21/24 

 

College Tuition Trends Project Proposal 

 

We are looking at college tuition data over the past decade. We are examining trends in tuition change in relation to many considerations such as inflation rates, geographic location, type of institution,
etc. This data is all provided by the Department of Education which mandates that colleges release information regarding tuition. This is valuable information that prospective or current students can use to make
important decisions about their education. We think that having detailed, intuitive, and interactive display of this information can make it more accessible for those students and their families. 

The data, accessible via this link, is the Department of Education’s College Affordability and Transparency List. Each year is presented by a separate data file. The files track in the area of 3500 Title
IV institutions throughout the US. The data contains information about the type of institution, tuition, tuition change, etc. at the individual level, and a variety of aggregate statistics. All of the data is
tabular, and fields include categorical information about the institution type and state, nominal data for the name of the institution, and numerical data for all tuition information.  

The data for the inflation rates can be found via this link, and is the inflation rate calculated using the consumer price index published by the Bureau of Labour Statistics. We will be transforming the
data to be the average for the year instead of monthly. The data is tabular and has been converted to a csv file.  

 

In 2019 an article entitled “The Rise and Fall of College Tuition Inflation” was published and specifically refers to the NCES data we are using. It is praised for its detailed breakdown of tuition prices
based on type of institution. It mostly focuses on a broad overview of the relationship between college tuition inflation and national inflation over a large period. They found that college tuition inflation
rates were not correlated with the rate of core inflation and presented this using two simple line plots. 

	 

College Board published a full report on “Trends in College Pricing 2023” and the accompanying powerpoint presentation provides a variety of data visualizations that examine the inflation of tuition
across three decades 1993-2023. It uses various data visualizations, such as tables and charts, to depict trends in tuition fees, enrollment-weighted average budgets, and inflation. The use of these
visualizations facilitates an easier understanding of complex data; however, their effectiveness could be enhanced by incorporating interactive elements that allow viewers to explore data more deeply or by simplifying some of the more complex charts for better clarity and quicker insigh	 

The visualization from the U.S. News & World Report clearly shows a 20-year trajectory of rising tuition costs at different types of universities. It provides a comparative look at private versus public
institutions, distinguishing between in-state and out-of-state tuition. The steep upward trends, particularly for private and in-state public tuition, are striking. However, this visualization could benefit from
additional context such as average family income growth, to assess affordability, or including net tuition costs after aid, to present a more complete financial picture for prospective students. # Project-Proposal
