
# 🎬 Movies Data Analysis Dashboard  

Interactive Movies Data Analysis Dashboard using MS Excel with Investment vs Return insights.

---

## 1. Project Title  

**Movies Data Analysis Using MS Excel**

---

## 2. Project Overview  

This project focuses on analyzing a Movies dataset to uncover meaningful insights about movie performance, audience preferences, and industry trends. The dataset includes information such as movie titles, genres, directors, release years, ratings, revenue, runtime, and audience votes.

The primary objective of this project is to transform raw movie data into actionable insights through data cleaning, pivot analysis, and interactive dashboard visualization.

Through this analysis, the project aims to:

- Identify the most popular and most profitable movie genres  
- Analyze rating trends over different years  
- Determine the top-performing movies and directors  
- Understand overall industry growth patterns  

The final dashboard presents key metrics and visual insights in a clear and interactive format.

---

## 3. File Details  

### 📂 Raw Dataset Folder  
- `Movies.csv`

### 📂 Cleaned Dataset Folder  
- `Movies_cleaned.xlsx`

### 📂 Pivot Tables and Calculations Folder  
- `Movies_pivot_analysis1.xlsx`  
- `Movies_pivot_analysis2.xlsx`

### 📂 Dashboard Folder  
- `Dashboard_image.jpg`

---

## 4. Data Dictionary  

| Column Name | Data Type | Description |
|-------------|----------|-------------|
| id | Integer | Unique identifier assigned to each movie or TV show |
| title | Text | Name of the movie or TV series |
| content_type | Text | Type of content (Movie, TV Series, Limited Series, etc.) |
| genre_primary | Text | Main genre/category of the content |
| genre_secondary | Text | Secondary genre of the content (if applicable) |
| release_year | Integer | Year the content was released |
| duration_minutes | Integer | Total runtime in minutes |
| rating | Text | Content certification rating (e.g., PG, R, TV-MA) |
| language | Text | Primary language of the content |
| country_of_origin | Text | Country where the content was produced |
| imdb_rating | Decimal | IMDb rating score (0–10) |
| production_budget | Decimal | Budget spent on production |
| box_office_revenue | Decimal | Revenue generated at the box office |
| number_of_seasons | Integer | Number of seasons (for TV series) |
| number_of_episodes | Integer | Total number of episodes (for TV series) |
| is_netflix_original | Boolean | TRUE/FALSE indicator |
| added_to_platform | Date | Date added to platform |
| content_warning | Boolean | TRUE/FALSE indicator |

---

## 5. Cleaning Notes  

- Extracted numeric portion from movie ID  
- Removed original ID column  
- Sorted dataset for better readability  
- Verified column headers and formatting  

---

## 6. Analytics View  

The dashboard provides:

- Total Content Count  
- Average Duration  
- Average IMDb Rating  
- Total Production Budget  
- Total Box Office Revenue  
- Total Episodes  
- Total Seasons  

### 📊 Visual Analysis Includes:

- Content Type Wise Content Count  
- Duration Distribution  
- Average IMDb Rating by Content Type  
- Investment vs Return (Budget vs Revenue)  
- Country Wise Comparison  
- Global Distribution Map  

---

## 7. Dashboard Preview  

![Dashboard Preview](Dashboard_image.jpg)

---

## 8. Conclusion  

The analysis highlights a strong relationship between production investment and box office performance. Movies dominate revenue and budget contribution, while TV Series contribute significantly in terms of engagement and episodes.

The dashboard provides a comprehensive view of content distribution, financial performance, and global trends.
