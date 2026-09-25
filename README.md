# Netflix Tableau Dashboard

## Project Overview

This project is an interactive **Netflix Content Analytics Dashboard** created using **Tableau**.

The dashboard analyzes Netflix movies and TV shows using different dimensions such as content type, genre, rating, release year, country, duration, and date added.

The objective is to explore the Netflix content library and present the information through interactive visualizations and filters.

---

## Dashboard

The Tableau dashboard provides an overview of Netflix content through multiple visualizations, including:

- Movies and TV Shows distribution
- Movies and TV Shows by release year
- Top 10 genres
- Movies and TV Shows by country
- Ratings distribution
- Content rating analysis
- Duration information
- Date added analysis
- Genre analysis
- Title and type filtering
- Content description

---

## Dataset

The dashboard uses the `netflix_titles` dataset.

The main fields available in the dataset include:

| Field | Description |
|---|---|
| Show Id | Unique identifier for each Netflix title |
| Type | Type of content such as Movie or TV Show |
| Title | Name of the movie or TV show |
| Director | Director of the title |
| Cast | Cast members associated with the title |
| Country | Country associated with the title |
| Date Added | Date when the title was added to Netflix |
| Release Year | Original release year |
| Rating | Content rating |
| Duration | Duration of the movie or number of seasons |
| Listed In | Genre/category information |
| Description | Description of the title |

---

## Key Dashboard Analysis

### 1. Movies and TV Shows Distribution

Shows the distribution of Netflix content between:

- Movies
- TV Shows

This provides an overview of the content mix available in the dataset.

---

### 2. Total Movies and TV Shows by Year

A time-based visualization showing how the number of movies and TV shows varies across release years.

This helps analyze the distribution of Netflix content across different years.

---

### 3. Top 10 Genres

Displays the top 10 genres/categories based on the available Netflix content.

This helps identify the major content categories represented in the dataset.

---

### 4. Movies and TV Shows by Country

Shows the geographical distribution of Netflix content based on country.

This provides an overview of the countries represented in the Netflix dataset.

---

### 5. Ratings Analysis

The dashboard includes rating-based visualizations to analyze the distribution of Netflix titles across different content ratings.

Examples of ratings represented in the dataset include:

- TV-MA
- TV-14
- TV-PG
- R
- PG-13
- PG
- G
- NR
- TV-G
- TV-Y
- TV-Y7

---

### 6. Duration Analysis

The dashboard provides information about the duration of Netflix content.

For movies, duration is represented in minutes.

For TV shows, duration can represent the number of seasons.

---

### 7. Date Added Analysis

The `Date Added` field is used to analyze when titles were added to Netflix.

This allows the dashboard to explore Netflix content based on its addition date.

---

### 8. Genre Analysis

The dashboard includes genre-based analysis using the `Listed In` field.

This allows users to explore different categories associated with Netflix titles.

---

## Interactive Filters

The dashboard provides interactive filters that allow users to explore the dataset.

Available filters include:

- Type
- Title
- Rating
- Release Year
- Date Added
- Genre

Users can apply filters to explore specific types of Netflix content.

---

## Dashboard Worksheets

The Tableau workbook contains the following worksheets:

1. Date Added
2. Description
3. Duration
4. Movies & TV Shows Distribution
5. Rating
6. Ratings
7. Release Year
8. Total Movies & TV Shows by Years
9. Top 10 Genre
10. Total Movies and TV Shows by Country
11. Genre

These worksheets are combined to create the final Netflix dashboard.

---

## Tools & Technologies

### Tableau

Used for:

- Data visualization
- Dashboard creation
- Interactive filtering
- Data analysis
- Charts and graphs
- Dashboard layout

### Dataset

Netflix titles dataset containing information about movies and TV shows.

---

## Dashboard Workflow

```text
Netflix Dataset
       |
       v
Data Preparation
       |
       v
Connect Dataset to Tableau
       |
       v
Create Worksheets
       |
       v
Create Charts & Visualizations
       |
       v
Add Filters
       |
       v
Combine Worksheets
       |
       v
Netflix Dashboard
