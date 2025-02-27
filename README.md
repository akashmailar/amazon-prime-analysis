# Amazon Prime TV Shows And Movies Data Analysis

## Project Type

Exploratory Data Analysis (EDA)


## Contribution

Individual


## Project Summary

In today's competitive streaming industry, platforms like ***Amazon Prime Video** are constantly expanding their content libraries to cater to diverse audiences. With a growing number of shows and movies available, data-driven insights play a crucial role in understanding trends, audience preferences, and content strategy.

This **Amazon Prime TV Shows and Movies Data Analysis** project focuses on exploring and analyzing content available on ***Amazon Prime***. The dataset consists of two CSV files: `titles.csv` and `credits.csv`, providing comprehensive information on movies, TV shows, ratings, popularity, genres, and cast/crew details. The dataset specifically contains data available in the **United States**.

By performing an in-depth analysis, this project aims to uncover insights into the platform's content distribution, user preferences, and trends over the years. It enables stakeholders to make data-driven decisions to enhance content recommendations and acquisitions.

---

## Dataset Overview

**1. `titles.csv`**

Contains details about TV shows and movies, including:

- Title name

- Release year

- Age certification

- IMDB rating

- Genres

- Duration

- Number of seasons (for TV shows)

**2. `credits.csv`**

Contains details about the cast and crew involved, including:

- Person ID

- Name

- Role (actor, director, etc.)

- Title ID (linking to `titles.csv`)

The combination of these datasets allows for a comprehensive exploration of ***Amazon Prime***'s content offerings.

---

## Objectives of the Project

- Perform data cleaning and preprocessing to handle missing and inconsistent values.

- Explore trends in movie and TV show releases over the years.

- Analyze IMDB ratings to understand the distribution and audience preferences.

- Identify the most popular genres and content types.

- Examine the influence of top actors and directors on content success.

- Discover patterns in regional content and its popularity.

- Utilize visualizations to present findings effectively.

---

## Technologies & Libraries Used

The project leverages various data science tools and libraries for data processing, analysis, and visualization:

- **Python** for data handling and analysis.

- **Jupyter Notebook** for interactive data exploration.

- **Pandas** and **NumPy** for data manipulation.

- **Matplotlib** and **Seaborn** for data visualization.

---

## Project Structure

    Amazon_Prime_Data_Analysis/
    │-- data/
    │   │-- titles.csv
    │   │-- credits.csv
    │-- notebooks/
    │   │-- Amazon_Prime_Data_Analysis_EDA.ipynb
    │-- README.md
    │-- requirements.txt

---

## How to Use the Project

1. Clone this repository:

    ```
      git clone https://github.com/akashmailar/amazon-prime-analysis.git
    ```

2. Install dependencies:

    ```
      pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook to explore the analysis:

    ```
      jupyter notebook Amazon_Prime_Data_Analysis_EDA.ipynb
    ```

---

## Results & Insights

- The most common genres on Amazon Prime.

- Trends in movie and TV show releases over the years.

- Popular actors and directors based on available data.

- Distribution of IMDB ratings and their impact on content selection.

---

## Conclusions & Future Work

- Further analysis could include sentiment analysis on user reviews.

- Comparing Amazon Prime's content strategy with competitors (Netflix, Hulu, etc.).

- Using machine learning to predict movie success based on features.

---

## Author

- [Akash Mailar](https://github.com/akashmailar)

---

## License

This project is licensed under the MIT License.

---

### Thank You!
