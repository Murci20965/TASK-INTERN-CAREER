# TASK-INTERN-CAREER
A comprehensive analysis of the top YouTube streamers dataset.

## Table of Contents:

1. Data Exploration
2. Trend Analysis
3. Audience Study
4. Performance Metrics
5. Content Categories
6. Brands and Collaborations
7. Benchmarking
8. Content Recommendations
9. Summary of Analysis Results

## Data Analysis with Python

### Overview
This Jupyter Notebook analyzes a dataset containing information about top YouTube streamers. The analysis covers various aspects, including trend analysis, audience study, performance metrics, content categories, brands and collaborations, benchmarking, and content recommendations. Popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn are utilized.

##### 1 - Data Exploration

Loads the dataset and provides an overview of its structure.
Explores the first 5 rows of the dataset.
Gets the shape of the dataset.
Descriptive statistics of the numerical columns of the dataframe.
Identifying key variables.
Checks for missing data.
Visualizes outliers using scatter plots and box plots.

##### 2 - Trend Analysis

Identifies trends among top YouTube streamers.
Creates visualizations for categories and performance metrics.
Analyzes correlations between subscribers, likes, and comments.

##### 3 - Audience Study

Studies audience distribution by country.
Visualizes the distribution of audiences by country.
Explores regional preferences for content categories using heatmaps.

##### 4 - Performance Metrics

Calculates and visualizes average performance metrics.
Displays average subscribers, visits, likes, and comments.

##### 5 - Content Categories

Explores the distribution of content categories.
Identifies categories with exceptional performance metrics.

##### 6 - Brands and Collaborations

Cleans the data and visualizes the relationship between performance metrics and brand collaborations.
Calculates correlation coefficients.

##### 7 - Benchmarking

Performs benchmarking by comparing content creators' performance against average values.

##### 8 - Content Recommendations

In the dynamic landscape of digital content consumption, the role of effective recommendations cannot be overstated. I will outline a strategic approach to elevate the content recommendation system on YouTube, fostering a more personalized and engaging user experience. By incorporating streamer categories and key performance metrics, we can aim to refine the algorithm, providing users with content that resonates with their unique preferences. I will explore the technical aspects, anticipated benefits, and potential challenges of implementing this enhancement, aligning with YouTube's commitment to delivering a tailored and enriching platform for its diverse user base.

###### a. Data Collection and Processing:
Continue collecting and updating data on YouTube streamers, including categories, performance metrics (likes, comments, visits, subscribers), and other relevant information.
Clean and preprocess the data to handle missing values, outliers, and any inconsistencies.

###### b. Feature Engineering:
select and transform variables such as likes, visits, subscribers to create a good predictive model using machine learning. this is a good way of enhancing predictive models as it involves isolating key information, highlighting patterns and bringing in someone with domain expertise.

###### c. Machine Learning Model:
Train a machine learning model to predict user preferences based on historical data. Use a recommendation algorithm such as collaborative filtering, content-based filtering, or a hybrid approach.

###### d. Collaborative filtering:
Recommend content based on the preferences of users with similar viewing behaviors.

###### e. Personalized Recommendations:
Provide personalized recommendations for each user by considering the preferences of users.
Utilize the machine learning model to dynamically adjust recommendations as user preferences evolve.

###### f. Trending and Popular Content:
Incorporate a section for trending and popular content in different categories to attract users to discover new streamers and content.


## Summary of Analysis Results

##### Category Insights
The dominant content category in the dataset is "Música y baile," reflecting a substantial presence and engagement within this genre.

##### Audience Distribution by Country
Ecuador, a South American country, stands out for having the most extensive audience distribution among the analyzed YouTube streamers.

##### Average Performance Metrics
In the dataset, the average metrics across all streamers are as follows:

- Average Subscribers: 21894400.0
- Average Visits: 1209446.3155
- Average Likes: 53632.592
- Average Comments: 1288.768

##### Correlation Between Visits and Brand Collaborations
Correlation between Visits and Brand Collaborations is 0.24520315821049435 which denotes positive correlation coefficient, suggesting a tendency for increased brand collaborations as the number of visitors to a channel rises.

##### Top-Performing Content Creator
Mr Beast is on top among content creators, having the highest number of subscribers and visits.
