# netflix-data-analysis
## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Netflix Movies dataset using Python. The objective is to clean, preprocess, analyze, and visualize movie data to uncover meaningful trends related to genres, ratings, popularity, and release years.

The project demonstrates the complete data analysis workflow, including data cleaning, feature engineering, statistical analysis, and visualization.

---

## 📂 Dataset

The dataset contains information about nearly **9,800+ movies**, including:

- Movie Title
- Release Date
- Popularity
- Vote Count
- Vote Average
- Genre
- Original Language
- Movie Overview
- Poster URL

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Explored dataset dimensions and column information.

### 2. Data Cleaning
- Removed missing values.
- Converted data types for numerical columns.
- Converted release dates into datetime format.
- Extracted release year from the date.
- Removed unnecessary columns such as:
  - Overview
  - Original Language
  - Poster URL

### 3. Feature Engineering
- Categorized movie ratings into:
  - Popular
  - Average
  - Below Average
  - Not Popular
- Split multiple genres into individual genres for detailed analysis.

### 4. Exploratory Data Analysis
Performed analysis on:

- Distribution of movie genres
- Movie ratings
- Popularity scores
- Vote counts
- Release year trends
- Genre frequency
- Relationship between popularity and ratings

### 5. Data Visualization
Created visualizations to better understand:

- Most common genres
- Genre distribution
- Movie release trends
- Rating categories
- Popularity patterns

---

## 📈 Key Insights

- Drama is the most frequently occurring movie genre in the dataset.
- Comedy and Action are also highly represented.
- Science Fiction movies have gained popularity in recent years.
- Western movies appear less frequently in modern releases.
- Most movies fall within the Average and Popular rating categories.

---

## 📁 Project Structure

```
Netflix-Movies-EDA/
│
├── Netflix_EDA.ipynb
├── mymoviedb.csv
├── README.md
```

## 📚 Learning Outcomes

This project helped in gaining practical experience with:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Handling Missing Values
- Data Type Conversion
- Statistical Analysis using Pandas
- Working with Real-world Datasets

---

## 📌 Future Improvements

- Interactive dashboard using Power BI
- Movie recommendation system
- Sentiment analysis using movie overviews
- Predictive analysis using Machine Learning
- Interactive web application using Streamlit

---

## 👨‍💻 Author

**Litile Gupta**
