# Project Highlight Report #
*Chao Pan*
&nbsp;

## Business Intelligence Projects ##
### Project 1: Should Watershed Enter the Short-term Rental Market?
April, 2016

Background: 
Watershed Properties is a residential property management company. My job is to persuade Watershed’s management team to pursue a new strategy for managing its properties that will increase their profits using data analysis skills. The core question is whether Watershed should expand into a different market: short-term rentals. 

During the process, I extracted relevant data from the company's database using MySQL and built up a linear regression model to predict the occupancy rate of each property according to their region, identifed the best opportunities for Watershed to increase revenue and maximize profits, while managing any new risks and within their budget. Finally I created a Tableau dashboard to show Watershed executive the results of a sensitivity analysis.

[`Interative Dashboard Report`](https://public.tableau.com/views/ShouldWatershedEntertheShort-termRentalMarket-ChaoPan/DashboardHistogram?:embed=y&:display_count=yes)

Screeshot of Dashboard:
![Screeshot](http://i.imgur.com/tQlwHgI.png)

The final conclusions are:
1. I recommend Watershed to convert 16 individual properties into short tem rental market with $480k initial capital investment
2. Main locations will be Miami FL, Austin TX, Palo Alto CA, San Diego CA and New York.
3. I suggest to convert the apartments in the following order which accords with their profitablity: 2-bedroom house first, 1-bedroom house second then 2 bedroom apartment. 
4. The analysis indicates that Watershed would benefit from $900k of increased profits during the first year, and generate yearly profits of $800k every year thereafter if my recommendation is enacted.


### Project 2: Recommendations for Dognition Business Process Change
Jan, 2016

Background:
Dognition (http://www.dognition.com) is a company that teaches people how to build a deeper connection with their dogs by giving people opportunities to test their dog’s personality and capabilities. 

My role is to help them figure out what business changes they could implement to increase the number of tests users complete on their website. 

I extracted and cleaned the data from their database and constructed some analysis and presented recomendations for their business process change on marketing and product design.

[`Interative Dashboard Report`](https://public.tableau.com/views/RecommendationsForDognitionBusinessProcessChange/Final?:embed=y&:display_count=yes&publish=yes)

Screenshot of Some Viz:
![Screeshot](http://i.imgur.com/MCfqmPB.png)



### Project 3: 2016 Presidential Campaign Finance Analysis: Trump vs. Clinton
July, 2017

Background:
I create a visualization of 2016 Presidential Campaign Finance, specifically on Trump and Clinton. The dataset is from fec.gov. It turns out that the finance amount ratio in each state basically accords with state political affliations. Clinton has a advantage on the total finance amount. Different states have different patterns in terms of donor composition.

[`Interative Dashboard Report`](https://public.tableau.com/views/donor_0/Story1?:embed=y&:display_count=yes&publish=yes)

Screenshot of Dashboard:
![Screeshot](http://i.imgur.com/38tzU8J.png)




&nbsp;

## Data Science / Machine Learning Projects

### Project 1: Predict Red Wine Quality

Background:
In this project, I explored a dataset that contains 1,599 red wines with 11 variables on the chemical properties of the wine. By performing this analysis, I seek to answer the guiding questions: Which chemical properties influence the quality of red wines. 

At the end, I found the following features have important influences on the quality of red wines. Positive: Alcohol percentage, Sulphates, Citric acid. Negative: Volatile acidity. Among those, alcohol percentage is the most powerful predictor of the quality of wine.

`Project Report`: http://wikichao.com/projects/red_wine.html  *(VPN is needed)*

Screenshot of Some Viz:
![Screenshot](http://i.imgur.com/EiiDR3g.png)
![Screeshot](http://i.imgur.com/jDgb5GT.png)


### Project 2: Identifying Fraud at Enron Using Emails and Financial Data
Background:
In 2000, Enron was one of the largest companies in the United States. By 2002, it had collapsed into bankruptcy due to widespread corporate fraud. In the resulting Federal investigation, a significant amount of typically confidential information entered into the public record, including tens of thousands of emails and detailed financial data for top executives.

In this project, I will apply machine learning techiques to build a person of interest identifier based on financial and email data made public as a result of the Enron scandal. There is an additonal hand-generated list of persons of interest in the fraud case, which means individuals who were indicted, reached a settlement, or plea deal with the government, or testified in exchange for prosecution immunity.

`Project Report`: http://wikichao.com/projects/enron_fraud.html *(VPN is needed)*


### Project 3: Predicting Stock Market Performance Using Machine learning

Background:
Applying support vector machine techique to "predict" the stock performance based on historical data.
Firstly, I downloaded the scraped historical financial data of SP500 companies from Yahoo finance.
Then I did some feature engineering and data merge. Features are DE Ratio,Trailing P/E, Profit Margin, Revenue Per Share, etc. The label is the binary comparsion of the percentage of stock price change of each company with sp500 stock price change after 1 year.

After the data wrangling process, I applied SVM algorithm to predict the change of stock price of each company after 30 days then validate with the actual data. It turns out that my simple machine learning trading algorithm beat the market "in theory".

`Codes`: https://github.com/Chaology/svm-stock-mkt


### Project 4: Author Attribution - Who Wrote "The Fatal Conceit"? 

Background:
There is a scholarly debate on how much influence William Warren Bartley had had on the work "The Fatal Conceit" of Nobel Prize Laureates F.A. Hayek. Officially, Bartley was the editor who prepared the book for publication once Hayek fell ill in 1985. However, the inclusion of material from Bartley's philosophical point of view and citations that other people provided to Bartley have led to questions about how much of the book was written by Hayek and whether Hayek knew about the added material. Bruce Caldwell thinks the evidence "clearly points towards a conclusion that the book was a product more of [Bartley's] pen than of Hayek's. ... Bartley may have written the book".

I analyzed Hayek and his editor's writing style (commonly used word using the bag of words) to validate who is more likely be the author of "The Fatal Conceit".

`Codes`: https://github.com/Chaology/author-attribution

&nbsp;

## Web Development Projects 
*Note: VPN is needed to access the following sites.*
- Web app:  https://easymemo.org
*(I developed a memo app for fun)*
- CCA conference website:  https://ccaconference.org  
*(I helped Zhuangzi Institute, an economic institute, delevop their conference website from scratch.)*


## Simple Game Projects
Some arcade games I coded for fun: https://github.com/Chaology/arcade-games
Try the [spaceship game](http://www.codeskulptor.org/#user41_lRhjb68M9i9SZ4S.py) if you are interested.





















