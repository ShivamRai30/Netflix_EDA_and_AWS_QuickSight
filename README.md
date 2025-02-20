# Netflix-Exploratory-Data-Analysis
![https___dev-to-uploads s3 amazonaws com_uploads_articles_hjukkwcishwdbbo3vp5m-1](https://github.com/user-attachments/assets/efb853df-b3d9-46a0-8319-c4093ff7613d)


### Colab Link= <a href="https://colab.research.google.com/drive/1_wvfmxya7aFfkNxXqsTZkO2abz86nllC?usp=sharing">View_Me</A>
#### Note: As dynamic charts are not supported on Github, I am sharing my colab link below. Please care to take a look at it 😊

# Project Overview
This project delves into the fascinating world of Netflix data. Through exploratory analysis we uncover patterns, trends, and insights hidden within the streaming giant’s vast content library. Whether you’re a data enthusiast, a curious viewer, or a business strategist, this EDA provides valuable takeaways.

# About Dataset
The Netflix dataset contains the records of content that has been uploded on Netflix from around the world since 2008, the year netflix went online. The datasets holds record of around 8800 movies and tv shows along with their title, director, cast, country, release_year, duration, rating, discription etc. which spread across 12 columns. The dataset contains record till year 2021.
* show_id: Gives the information about show id.
* type: Gives information about 2 different unique values one is TV Show and another is Movie.
* title: Gives information about the title of Movie or TV Show.
* director: Gives information about the director who directed the Movie or TV Show.
* cast: Gives information about the cast who plays role in Movie or TV Show.
* country: Gives information about the Name of country.
* date_added: Gives information about the tv shows or movie released.
* release_year: Gives information about the year when Movie or TV Show was released.
* rating: Gives information about the Movie or TV Show are in which category (eg like the movies are only for students, or adults, etc).
* duration: Gives information about the duration of Movie or TV Show.
* listed_in: Gives information about the genre of Movie or TV Show.
* description: Gives information about the description of Movie or TV Show.

# Tools and Libraries used
* 1] Google Colab
* 2] Pandas
* 3] Numpy
* 4] Plotly.express
* 5] Plotly.graph_object
* 6] Plotly.subplots
* 7] Json

# Steps Performed
## Data Wrangling:
* Loading Dataset
* Checking Shape
* Checking Null Values
* Filling Null Values
* Checking Duplicate Records 

## Feature Engineering:
* Extracting Features
* Extracting Country
* Creating year added column
* Creating month added column
* Creating day added column
  
## Exploratory Data Analysis:
* Plotting distribution of Movies and Tv Shows on Netflix
* Creating view of ontent uploaded over the years on Netflix
* Plotting distribution of content on Netflix based upon release year
* Visualizing average number of Movies and TV Shows released on Netflix every month
* Creating view of Top 25 countries with most content on Netflix
* Plotting top Movie and TV Show Generes on Netflix'
* Creating view of top 15 Directors from India, USA, UK on Netflix with most content 
* Creating view of top 15 Actor/Actress from differnt countries on Netflix with most content
* Plotting distribution of Movies and TV Shows on Netflix based on their ratings
* Creating view of content uploaded over the years on Netflix America Vs India
* Creating view of content uploaded in 2021 on Netflix America Vs India
* Visualizing average number of Movies and TV Shows released on Netflix in America and India every month
* Creating view of 2021 Indian and American Movies and TV Shows on Netflix
* Creating view of Oldest Movies and TV Shows on Netflix
* Creating a worldmap representing content uploaded per country.

# Conclusion
### In this EDA journey through Netflix’s data, we’ve unveiled fascinating insights:
#### * Genre Trends: 
International movies and tv shows, drama and comedy dominate, but sci-fi and thrillers are rising stars.
#### * Release Patterns:
Content keeps rising and drops year-round during covid, with seasonal spikes.
#### * Global Leaders:
USA, India, UK are at the top in terms of conent available
#### * Global Impact:
Netflix has reach spans continents from small to large nations.
