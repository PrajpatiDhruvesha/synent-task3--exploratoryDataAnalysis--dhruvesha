# Task 3: Exploratory Data Analysis (EDA)

## Problem Statement

Analyze the Netflix Movies Dataset to identify trends, patterns, and relationships within the data using statistical analysis and visualizations. The goal is to discover insights related to content releases, popularity distribution, genres, ratings, and feature correlations.

---

## Dataset Details

### Dataset Name
Netflix Movies Detailed Dataset (Up to 2025)

### Description
The dataset contains detailed information about Netflix movies and shows, including release year, genres, popularity scores, ratings, and other attributes. It is used to analyze content trends and viewer preferences over time.

### Features
- Release Year
- Genres
- Popularity
- Ratings
- Other numerical and categorical attributes

---

## Approach

### 1. Data Loading
- Imported the dataset using Pandas.
- Loaded the Netflix dataset into a DataFrame.

### 2. Data Understanding
- Examined dataset structure using `df.info()`.
- Generated summary statistics using `df.describe()`.

### 3. Missing Value Analysis
- Checked for missing values using `df.isnull().sum()`.

### 4. Correlation Analysis
- Selected numerical columns from the dataset.
- Computed the correlation matrix.
- Visualized relationships using a correlation heatmap.

### 5. Trend Identification
- Analyzed yearly content release trends using a line chart.
- Observed changes in content production over time.

### 6. Genre Analysis
- Identified the top 10 most common genres.
- Visualized genre distribution using a bar chart.

### 7. Popularity Distribution
- Analyzed popularity scores using a histogram.
- Examined how content popularity is distributed across different ranges.

---

## Results

### Correlation Heatmap
- Revealed relationships between numerical features.
- Helped identify positively and negatively correlated variables.

### Content Release Trends
- Showed how the number of Netflix releases changed over the years.
- Highlighted periods of increased content production.

### Genre Analysis
- Identified the most frequently occurring genres in the dataset.
- Provided insights into popular content categories.

### Popularity Distribution
- Displayed the spread of popularity scores across Netflix content.
- Helped understand viewer engagement patterns.

---

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
