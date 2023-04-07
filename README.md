# 2019 - 2022 PGA Shots Gained vs Tournament Finish

This was a small analytics project I wanted to do to see relationships between where golfers place in a tournament and their shots gained statistics.

I started by finding and downloading raw PGA data from Advanced Sports Analytics (https://www.advancedsportsanalytics.com/pga-raw-data). I will include the specific raw data that I downloaded, but know that the years are 2019 - 2022. However, their website allows you to go as far back as 2015 if anyone decides to use their data.

After downloading, I uploaded the raw CSV file into Google Colab so that I could use Python and Pandas to clean and filter the data. The code here is rather simple, but it gave me the information that I was wanting. There were a few missing values in the shots gained data, and I initially decided to fill null values with the mean value. However, after doing this it was giving me inconsistent, or rather "too consistent" data points on my visualization, and I found myself exlcuding them from the data when using Tableau. For this reason, I decided to drop the null values all together. 

In my code, I kept my function for filling the null values with the mean as a comment on the off chance anyone wanted to try something for themselves. I also commented out a line of code that I used to save the cleaned data to a CSV file that I could upload to Tableau.

Once the data was clean, I did some visualization within Python using Plotly so that I could get some more practice there. My main focus was getting this data cleaned so that I could attempt a dashboard using Tableau. The dashboard is public on my account (https://public.tableau.com/app/profile/derek.tawney/viz/PGASGData/Dashboard1).
