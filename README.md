Project Explanation: IMDb Movie Review Sentiment Analysis

Introduction:
This project aims to conduct sentiment analysis on movie reviews fetched from IMDb using IMDbPY and analyze the sentiment distribution. Sentiment analysis helps understand the opinions, emotions, and attitudes expressed in textual data. The selected movie for this analysis is "The Dark Knight."

Methodology:

Data Acquisition:
The IMDbPY library is utilized to search for the movie by title and fetch its reviews. If the movie is found, its reviews are collected for analysis.

Data Cleaning:
The fetched reviews contain HTML tags and unwanted characters. Beautiful Soup is employed to remove HTML tags, and regular expressions are used to clean the text by eliminating special characters and converting it to lowercase for consistency.

Sentiment Analysis:
TextBlob, a natural language processing library, is employed for sentiment analysis. Each cleaned review is processed, and sentiment polarity is assessed. Reviews are categorized as positive, negative, or neutral based on their polarity scores.

Results Visualization:
The sentiments identified in the reviews are visualized using a pie chart generated with Matplotlib. The pie chart showcases the distribution of positive, negative, and neutral sentiments among the movie reviews.

Conclusion:
This project provides insights into the overall sentiments expressed by IMDb reviewers for the movie "The Dark Knight." By examining sentiment distributions, it helps in understanding the general emotional tone conveyed in the reviews, aiding in assessing audience opinions about the movie.
