# MovieLens Classic – Power BI Dashboard

An interactive Power BI dashboard developed for the **"Movie Talkies: Classic"** edition of MovieLens to analyze classic movies released up to the year 2000, user demographics, genre preferences, and movie rating patterns.

## 📌 Project Overview

MovieLens aims to understand viewer preferences and promote classic movies to both existing and newer audiences. This project transforms MovieLens movie, rating, and user data into an interactive business intelligence dashboard that explores movie characteristics, user engagement, demographics, and rating trends.

The dashboard addresses key questions around:

- Classic movie and genre distribution
- MovieLens user demographics and gender diversity
- Gender-wise genre preferences
- Overall movie ratings and genre distribution
- Geographic and demographic distribution of users
- Age and occupation-based engagement
- Top-rated movies and genres
- Relationship between user age and movie ratings
- Rating trends across movie release years and genres

## 📊 Dataset

The project uses three datasets:

### Movies
Contains information about movies and their genres.

- `movie_id`
- `movie_name`
- `genre`
- `year`

### Ratings
Contains user ratings given to movies.

- `user_id`
- `movie_id`
- `rating`
- `timestamp`

### Users
Contains demographic information about MovieLens users.

- `user_id`
- `age`
- `gender`
- `occupation`
- `zipcode`

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Data Cleaning & Transformation**
- **Data Visualization**

## 🔄 Data Preparation & Modeling

The three datasets were cleaned and transformed before analysis.

Key preparation steps included:

- Promoting the first row as column headers
- Cleaning and transforming relevant fields
- Establishing relationships between the Movies, Ratings, and Users tables
- Creating calculated columns and measures using DAX
- Grouping movie genres into broader genre-based categories
- Grouping movie release years into decades
- Creating user age groups
- Handling users with ages below 18 using occupation-based median age
- Removing redundant fields where necessary

### Data Model

The report follows a relational model where:

- `Users` → `Ratings`
- `Movies` → `Ratings`

The `Ratings` table acts as the central fact table connecting users and movies.

## 📈 Dashboard Pages

### 1. Movie Overview

Analyzes the classic movie landscape through:

- Total number of movies
- Distinct genres
- Total users
- Gender diversity
- Gender-wise genre preferences
- Average movie rating
- Movie distribution across genre groups and decades

### 2. User Demographics & Engagement

Explores the MovieLens user community through:

- Age and gender distribution
- Geographic distribution of users
- Average ratings across occupations and age groups
- Interactive decade and occupation filtering

### 3. Movie Ratings & Trends

Focuses on movie ratings and trends through:

- Top-rated movies
- Top-rated genres
- Age vs. average rating
- Average rating across movie release years
- Interactive filtering by decade, genre, age group, and occupation
- Bookmark-based toggle between movie and genre treemaps

## 📌 Key Insights

The dashboard provides a consolidated view of:

- The scale and genre composition of classic movies
- Gender diversity within the MovieLens community
- Differences in genre preferences across genders
- How ratings vary across demographic groups
- Geographic concentration of users
- Differences in movie engagement across age groups and occupations
- Top-rated movies and genre groups
- Changes in average ratings across movie release years

## 🎯 Business Objective

The analysis can support MovieLens in developing the **"Movie Talkies: Classic"** edition by identifying:

- Popular classic movie categories
- Viewer demographic patterns
- Genre preferences across user segments
- Potential audience segments for classic content
- Rating trends that can inform content curation and promotion

## 📂 Project Files

- `MovieLens_Classic_Dashboard.pbix` – Power BI dashboard
- `Business_Report.pdf` – Business report documenting the analysis
- `README.md` – Project documentation

## 👩‍💻 Author

**Aastha Pangaria**

Civil Engineering, IIT Bhubaneswar  
Interested in Data Science, Product Analytics, and AI-driven problem solving.
