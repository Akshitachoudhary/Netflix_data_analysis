# Netflix Data Analysis using Python
## Overview
This project analyzes a Netflix dataset using Python to uncover insights about movie genres, popularity, votes, and production trends. The goal is to identify patterns in viewer preferences and determine which genres or movies dominate Netflix’s catalog.
## Objectives

The analysis answers the following key questions:
1. What is the most frequent genre in the dataset?
2. Which genres have the highest votes?
3. What movie got the highest popularity and what’s its genre?
4. What movie got the lowest popularity and what’s its genre?
5. Which year has the most filmed movies?

##  Tools and Libraries Used

* **Python 3**
* **pandas** – for data manipulation and cleaning
* **numpy** – for numerical computation
* **matplotlib / seaborn** – for visualization
* **Jupyter Notebook** – for analysis and exploration
## 📊 Dataset Description

The dataset contains Netflix titles with columns such as:

* **Title**
* **Genre(s)**
* **Popularity**
* **Votes**
* **Release Year**
## Data Analysis Workflow

1. Import Libraries and Dataset
2. Data Cleaning
   * Removed null and duplicate values.
   * Split multiple genres using `str.split(', ')` and expanded using `explode()`.
   * Ensured numeric columns like votes and popularity were correctly typed.

3. Exploratory Data Analysis (EDA)
   * Counted frequency of each genre.
   * Calculated which genre had the highest votes and popularity.
   * Found movies with the highest and lowest popularity.
   * Identified the most active release year.

4. Visualization

## Results & Insights

### **Q1: What is the most frequent genre in the dataset?**

> **Thriller** is the most frequent genre, appearing in more than **14%** of all movies among 19 other genres.
### **Q2: Which genres have the highest votes?**

> **Thriller** again leads with the highest audience engagement, representing **25.5%** of the dataset (≈6520 movies) and accounting for over **18.5%** of total movie popularity.

### **Q3: What movie got the highest popularity? What’s its genre?**

>  **Spider-Man: No Way Home** has the highest popularity rate in the dataset.
>  **Genres:** Action, Adventure, and Science Fiction

### **Q4: What movie got the lowest popularity? What’s its genre?**

> **The United States, Thread** has the lowest popularity rating.
> **Genres:** Music, Drama, War, Sci-Fi, and History

### **Q5: Which year has the most filmed movies?**

> **Year 2020** recorded the highest number of filmed movies in the dataset.

## Conclusion

* **Thriller** dominates Netflix both in terms of **frequency** and **viewer votes**.
* **2020** was the most active year for movie releases.
* **Spider-Man: No Way Home** stood out as the most popular title overall.
* The dataset shows a consistent viewer preference for intense, story-driven genres like **Thriller**, **Action**, and **Adventure**.

## How to Run

1. Clone or download the repository.
2. Install dependencies:
3. Open the notebook:
4. Run all cells to reproduce the results and visualizations.

## Author

**Akshita Choudhary**
🎓 *B.Tech in Artificial Intelligence and Machine Learning*

