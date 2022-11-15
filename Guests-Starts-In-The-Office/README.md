# Guests Stars in The Office

![The Office](https://assets.datacamp.com/production/project_1170/img/office_cast.jpeg)

The Office! What started as a British mockumentary series about office culture in 2001 has since spawned ten other variants across the world, including an Israeli version (2010-13), a Hindi version (2019-), and even a French Canadian variant (2006-2007). Of all these iterations (including the original), the American series has been the longest-running, spanning 201 episodes over nine seasons.

In this notebook, we will take a look at a dataset of The Office episodes, and try to understand how the popularity and quality of the series varied over time. To do so, we will use the following dataset: datasets/office_episodes.csv, which was downloaded from Kaggle [here](https://www.kaggle.com/datasets/nehaprabhavalkar/the-office-dataset).

## Python Libraries
- Pandas
- Matplotlib

## Goals
Create a matplotlib scatter plot of the data that contains the following attributes:
- Each episode's episode number plotted along the x-axis
- Each episode's viewership (in millions) plotted along the y-axis
- A color scheme reflecting the scaled ratings (not the regular ratings) of each episode, such that:
- Ratings < 0.25 are colored "red"
- Ratings >= 0.25 and < 0.50 are colored "orange"
- Ratings >= 0.50 and < 0.75 are colored "lightgreen"
- Ratings >= 0.75 are colored "darkgreen"
- A sizing system, such that episodes with guest appearances have a marker size of 250 and episodes without are sized 25
- A title, reading "Popularity, Quality, and Guest Appearances on the Office"
- An x-axis label reading "Episode Number"
- A y-axis label reading "Viewership (Millions)"
- Provide the name of one of the guest stars (hint, there were multiple!) who was in the most watched Office episode. Save it as a string in the variable top_star (e.g. top_star = "Will Ferrell").

Bonus Step: Try to differentiate guest appearances not just with size, but also with a star.
