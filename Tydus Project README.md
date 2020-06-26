# KINGS COUNTY REAL ESTATE PROJECT

## Questions to ask

### What are 3 features that impact the housing price the most?

The reason for this question is simple. In order to invest or purchase the house, what factors you have to look into the most in order to bring out the best results. If you are selling the house, you can have a ball park of the appraisal value of your house to expect/inspect fairness.

## Outline:

### 1. Data Observation
#### 1.1 Data Observation
#### 1.2 Data Touch/Clean up for Observation
#### 1.3 Over view of the data

### 2. Data Cleaning
#### 2.1 Data Scrubbing/Clean Up - Categorical Columns
#### 2.2 Data Scrubbing/Clean Up - Non Categorical Columns
#### 2.3 Data Regression
#### 2.4 Key Features
#### 2.5 Multicollinearity

### 3. Visuallization
#### 3.1 Data Visuallization - Price vs Location
#### 3.2 Data Visualization - Price vs. House Size
#### 3.3 Data Visualization - Price vs. Grades
#### 3.4 Data Visualization - Best Sales Season

### 4. Future Work 

### 5. Conclusion

1. With data observation, I was able to find couple interesting facts about the data. There were few unknown factors to the data like duplicated ID, quick turn arounds of houses with large price jump, ouliers, null values, and different data types. After performing the clean up, I was able to have a better overview of the data.


2. To understand what features that impact the housing price the most, I had to perform further Data Cleaning and Scrubbing. I started by defining categorical and non catergorical columns. Found key features based on low p_values. Also tested Multicollinearity and removed columns accordingly. I added couple visuals to see how each clean up was able to bring up the accuracy of the regression model results.

    Starting data has R2_score of 0.747 with accuracy of 58.9%
    Final product of data has R2_score of 0.884 with accuracy of 88.4%
    
    3 Key Features that influence the housing price are size of living, location (zipcode, lat and long) and grades.


3. I have visualized the key features vs price to show how each features affects the pricing of the house. 
    
    By using scatter plot, I showed map the location of each houses and used the colors to make comparison of the prices.
    By using line graph, I visualized the the mean of housing prices according to zipcode. 
    By using joint plot, I graphed to show the correlation between price and house sizes
    Lastly, box plot shows how grades and price are positively correlated.
    

4. For future work, I would like to take a closer look at other features could make an impact on the housing prices.