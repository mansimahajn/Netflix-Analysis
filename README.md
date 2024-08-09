# Netflix Dataset Analysis

## About

This project involves a comprehensive analysis of a Netflix dataset to uncover insights and patterns in the content offered on the platform. By leveraging Python and various data visualization tools, the project aims to present clear and meaningful interpretations of the data, highlighting trends in content type, ratings, and more.

## Objective

The primary objective of this project is to analyze the Netflix dataset to uncover insights about the types of content available, their distribution over time, and the sentiment associated with content descriptions. By visualizing these patterns, we aim to provide a comprehensive overview of Netflix's content library, aiding in strategic decision-making and enhancing user experience.


## Libraries Used

1. numpy

2. pandas

3. seaborn

4. matplotlib

5. plotly

6. textblob



## Code Overview





### Data Loading and Preprocessing

The dataset was loaded using pandas and missing values were handled by using dropna and fillna methods. Columns were renamed for better readability, and unnecessary columns were dropped to streamline the analysis. The data was then grouped and categorized to facilitate deeper insights.



### Insights Derived


**Sentiment Analysis**: 

Analyzed the sentiment of content descriptions using TextBlob, categorizing them into Positive, Neutral, and Negative sentiments.
Visualized the sentiment distribution over the years to identify trends.


**Content Type Analysis**: 

Visualized the distribution of Movies and TV Shows on Netflix over the past 25 years.
Observed the ratio of Movies to TV Shows and how it has evolved.Ratings Distribution
Analyzed and visualized the distribution of content ratings using bar and pie charts.


**Country and Genre Analysis**:

Identified the top countries contributing to Netflix's content library.Analyzed the distribution of content by country and genre.



## Visualizations


**Vertical Bar Graph**:

Used for Sentiment Analysis of content descriptions.Displays the sentiment distribution of content descriptions over the years.


**Stack Plot**:

Used for Content Type Analysis.Shows the number of Movies and TV Shows released over the past 25 years.


**Horizontal Bar Chart**:

Used for Ratings Distribution.Compares the number of Movies and TV Shows for each rating.


**Pie Chart**: 

Used for Ratings Distribution.Illustrates the overall distribution of content ratings.


**Count Plot**: 

Used for Top Actors and Country and Genre Analysis.Displays the top 10 actors based on the number of titles and identifies the top countries contributing to Netflix's content library.


**Color Palette Plot**: Used to visualize Netflix brand colors.Displays the Netflix brand color palette using sns.palplot.



## Conclusion
This analysis provides valuable insights into Netflix's content library, highlighting trends in content types, sentiments, ratings, and contributions by country and genre. The visualizations offer a clear and comprehensive view of the data, aiding in strategic decision-making and enhancing user experience on the platform.
