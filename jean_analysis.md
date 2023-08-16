## Q2 analysis: 

### Question: Given the time period, which company has the most growth on stock price, and which company has the most decline on stock price?

### Most Growth:
X-axis: Represents time, specifically the quarters from Q1 2018 to Q2 2023.
Y-axis: Represents the stock price.
Lines: Each line represents one of the top 5 tickers with the greatest growth rate. The growth rate is calculated as the difference between the final and initial prices, divided by the initial price.
Annotations: The chart includes annotations (labels) at the end of each line, displaying the ticker name. This makes it easy to identify each line
Legend: The legend outside the plot area helps identify which color line corresponds to each ticker.
This chart provides a visual representation of the stocks that have experienced the most growth over the given period. We can easily compare their trends and see how they performed relative to one another.
We can see that from 2018 Q1 to 2023 Q2, NVIDIA Corporation, Tesla, Inc., and Apple Inc. has the most growth on stock price. Followed by Advanced Micro Devices, Inc. and Marathon Digital Holdings, Inc.. 

### Most Decline:
X-axis: Similar to the previous chart, it represents the quarters from Q1 2018 to Q2 2023.
Y-axis: Represents the stock price.
Lines: Each line represents one of the bottom 5 tickers with the greatest decline rate. The decline rate is calculated in the same way as the growth rate but focuses on negative values, indicating a loss in stock price.
Annotations: Annotations at the end of each line display the ticker name.
Legend: Similar to the previous chart, the legend helps identify which line corresponds to each ticker.
This chart provides insight into the stocks that have declined the most during the given time frame. It helps identify and analyze the companies that may be struggling or facing challenges in their respective markets.
And from the second chart, it shows that from 2018 Q1 to 2023 Q2, American Airlines Group Inc., JetBlue Airways Corporation, DISH Network Corporation, AMC Entertainment Holdings, Inc.	and Lloyds Banking Group plc has the most drop on stock price.

### Why is it important to know the growth and decline of stock price?
Investment Opportunities: Identifying stocks with high growth rates can highlight potential investment opportunities. Conversely, knowing the stocks in decline can signal which investments to avoid or reconsider.


Company Performance Analysis: Growth and decline metrics can be used to assess the performance of a company's management. For example, a company with consistently declining stock prices might be mismanaged or facing significant challenges that it's failing to address effectively.

Risk Management: For portfolio managers, understanding which stocks are growing and which are declining is crucial for risk management. They might decide to balance high-risk, high-growth stocks with more stable, low-growth ones.

Mergers & Acquisitions: Companies looking for acquisition targets might focus on declining tickers as potential buyout candidates. Similarly, growing companies might be viewed as potential threats or partners.


## Q3 analysis:
### Question: What is the average age of officers of these companies?
We first get data from Yahoo Finance about company background information. With 30 companies and all of their officers' age listed. 
Then we generated a box chart with the information including: 

Company Names on the x-axis: Each box in the plot corresponds to one company from the top_30_tickers. The companies are arranged in increasing order of their officers' mean ages. The company on the far left has the youngest average officer age, while the company on the far right has the oldest.

Officer Age on the y-axis: This represents the age of officers. The range of this axis shows the youngest and oldest officers among all the companies.

Boxes: For each company:

The bottom of the box represents the age of the youngest 25% of officers (1st quartile or Q1).
The top of the box represents the age of the youngest 75% of officers (3rd quartile or Q3).
The line inside the box is the median age of officers for that company.
The height of the box (IQR) shows the age range for the middle 50% of the officers.
Whiskers: These are the lines extending above and below the box.

The top whisker extends to the oldest officer's age within 1.5 times the IQR from the 3rd quartile.
The bottom whisker extends to the youngest officer's age within 1.5 times the IQR from the 1st quartile.
Red Dots: These represent the mean (average) age of officers for each company. By comparing the position of the red dot to the median line, you can tell if the average age is above or below the median.

Outliers: Dots above or below the whiskers, these represent officer ages that are unusually high or low compared to the rest of the officers for that company.

For more direct information, we also developed a bar chart to show the average age of officers of these companies. And we found that the Mean Age is 53.07, Median Age is 55.00 and Mode Age is 55. 

### Why is it important to know the average age of officers of these companies?
Diversity of Thought: Age can influence perspectives and decision-making processes. A mix of age groups among leadership might bring diverse viewpoints, combining both experience and fresh ideas, leading to a balanced approach to business strategy.

Succession Planning: An understanding of the age demographics of company officers can help shareholders and the board plan for the future. If many top executives are nearing retirement age, there may be a need for succession planning and leadership development initiatives.

Company Culture & Adaptability: Younger leadership may be more receptive to newer technologies, trends, or innovative business models. On the other hand, seasoned leaders might bring decades of industry knowledge and connections. Understanding the age mix can give insights into the company's adaptability and cultural leanings.

Investment Decisions: Some investors may look at the average age of company officers as a factor when considering the potential for innovation or stability in a company. For example, tech startups with younger leadership might be perceived as more innovative but potentially less stable than established companies with older leadership.
