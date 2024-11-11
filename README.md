# Netflix Data Analysis Project

![Netflix Logo](https://github.com/Dekay27/Sharpe_Ratio-Data_Analysis_Project/blob/main/images/annalized_sharpe_ratio.png)

**Netflix** has grown from a DVD rental service in 1997 to one of the largest entertainment and media platforms in the world. With a vast catalog of movies and series, Netflix data offers an excellent opportunity for exploratory data analysis.

This project focuses on analyzing Netflix movies from the 1990s, specifically exploring trends in movie durations and identifying characteristics of action movies from that decade. This analysis will provide insights for a production company specializing in nostalgic content.

## Table of Contents

- [Project Overview](#project-overview)
- [The Data](#the-data)
  - [netflix_data.csv](#netflix_datacsv)
- [Analysis Steps](#analysis-steps)
- [Key Findings](#key-findings)
- [Requirements](#requirements)
- [Conclusion](#conclusion)

## Project Overview

This analysis was conducted for a production company interested in nostalgic movies, specifically those released in the 1990s. The primary goals were to:
- Understand the distribution of movie durations for 1990s movies on Netflix.
- Identify trends within action movies from the 1990s, such as the number of short films (movies under 90 minutes).

The dataset used, `netflix_data.csv`, contains information about Netflix's catalog, including show types, titles, release years, durations, genres, and more.

## The Data

### **netflix_data.csv**

This dataset includes information on Netflix’s content, covering both movies and TV shows. Below is a summary of the key columns:

| Column         | Description                       |
|----------------|-----------------------------------|
| `show_id`      | Unique ID of the show             |
| `type`         | Type of content (Movie/TV Show)   |
| `title`        | Title of the content              |
| `director`     | Director of the show              |
| `cast`         | Cast of the show                  |
| `country`      | Country of origin                 |
| `date_added`   | Date added to Netflix             |
| `release_year` | Year of release                   |
| `duration`     | Duration of the content in minutes|
| `description`  | Description of the show           |
| `genre`        | Genre of the content              |

## Analysis Steps

1. **Data Import and Preprocessing**
   - Loaded the `netflix_data.csv` file using Pandas.
   - Filtered the data to only include movies released in the 1990s.

2. **Exploratory Data Analysis**
   - Visualized the distribution of movie durations for 1990s movies.
   - Focused on the subset of action movies from the 1990s, examining the count of movies with durations under 90 minutes.

3. **Visualization**
   - Created a histogram to show the distribution of movie durations for 1990s movies.
   - Used conditional filtering to determine the count of short action movies (less than 90 minutes) in the 1990s.

## Key Findings

- **Distribution of Movie Durations**: The histogram of movie durations shows the spread and frequency of different movie lengths during the 1990s.
- **Action Movie Insights**: Among 1990s action movies, a specific count of short movies (under 90 minutes) was identified, providing insights into the characteristics of action films from that period.

## Requirements

To run this analysis, you’ll need the following Python libraries:

- `pandas`
- `matplotlib`

You can install the dependencies with:

```bash
pip install pandas matplotlib
```

## Conclusion

This analysis provided valuable insights into Netflix's catalog of movies from the 1990s. By examining movie durations and focusing on action movies, we identified trends that could be useful for a production company targeting nostalgic content. Future analysis could explore additional genres or compare 1990s content to movies from other decades.