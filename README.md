# Personal-Dataset

Motivation:
My Anime List (MAL) can categorize anime data in several ways, such as score, ranking, or popularity. I decided to look at the MAL Database for 2020 and analyze the top 1000 popular animes. 
The question I am to answer is, "What is the score distribution of the top 1000 popular animes of 2020?"

Data Process:
I found a dataset by Hernan Valdivieso on Kaggle containing information from about 17562 animes, including names of the anime, scores, rankings, and popularity standing. The first step to clean the data was to include only the top 1000 popular animes. MAL categorizes each season of anime; for example, Attack on Titan seasons 1, 2, 3, and 4 are separately classified. I did not change this categorization.

Visualization:


Analysis:
To analyze this data, I began with a summary of the data and found Tukey's 5 number summary of the anime's scores which are as follows:

 Min.    : 3.410
 1st Qu. : 7.3
 Median  : 7.6
 Mean    : 7.669
 3rd Qu. : 8.140
 Max.    : 9.190

 Next, I created a boxplot of the score data and a histogram.
 The biggest outlier was "Pupa" having a score of 3.41. 
