# Summary

### Abstract
Using freely available data, I created a business plan to analyze web behavior with the goal of increasing percentage of sales from visits at a commercial website. I also used the data available to create a plan to potentially examine why visits do not convert to sales. I used Excel to summarize and analyze data, and Tableau to visualize data. 

### Design
An imaginary online clothing retailer wants to increase the number of sales they make. I used publicly available data to represent their site visits and purchases. From this data, I created a proposal on how they could use data analysis to find solutions to their problem. I proposed that I would use data that is not publicly available but the organization is likely to have in house. I would use this data to create a Markov model of behavior on the website that might help identify loss points. Additionally, I would look at “exit pages” – where the customer leaves the website – to see if there is something similar about them that can be adjusted to increase sales. 

### Data
Data is in an Excel File. A datapoint is one visit to the website. The dataset includes visits collected from February to December, excluding April; the dataset does not explain why it has no data for January and April. I used 9 continuous variables and one categorical variable to discuss how to create a model that would predict purchase or not. I created an additional continuous variable from one of the nine. The data were very clean. There were over 12,000 visits to the website; approximately 60 data points were removed for being “other” visitors rather than “returning” or “new” visitors, and two outliers were removed (spending 10 hours on the website). 

### Algorithms
I used Excel for preliminary data exploration with pivot tables, which yielded little insight into a business proposal. I used Tableau for more extensive data exploration with scatter plots and bar plots, which produced more insight into some broad types of visitors, and some good future paths. I used Python for a preliminary logistic regression of Google Analytics page values onto purchase. 

### Tools
Excel for initial EDA and for cleaning data
Tableau for visualization
Python for initial processing

### Communication
PowerPoint presentation
