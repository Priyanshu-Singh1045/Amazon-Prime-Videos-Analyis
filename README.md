# 🎬 Amazon Prime Videos Analysis

A complete **Exploratory Data Analysis (EDA)** and **Power BI Dashboard** project on the Amazon Prime Video catalog. This project analyzes thousands of movies and TV shows to uncover trends in content distribution, genres, ratings, release years, and country-wise production using Python and Power BI.

---

## 📌 Project Overview

Streaming platforms generate massive amounts of content every year. This project explores the Amazon Prime Video content library and answers key business questions through data analysis and visualization.

The project follows an end-to-end analytics workflow:

* Data Cleaning & Preprocessing using **Python**
* Exploratory Data Analysis (EDA) with **Pandas** and **Matplotlib**
* Business Insights from the dataset
* Interactive Dashboard creation in **Power BI**

The final dashboard enables users to interactively explore Prime Video's content by genre, country, rating, and release year.

---

## 🎯 Objectives

* Analyze the distribution of Movies vs TV Shows.
* Identify the most popular genres on Amazon Prime Video.
* Discover which countries contribute the most content.
* Analyze content ratings across the platform.
* Study release year trends and content growth over time.
* Build an interactive dashboard for business insights.

---

## 📊 Dashboard Preview

> Replace this section with a screenshot of your Power BI dashboard.

![Amazon Prime Dashboard](dashboard_preview.png)

---

## 📁 Dataset

The project uses the **Amazon Prime Titles Dataset** containing information about thousands of titles available on Prime Video.

### Dataset Features

| Column         | Description                 |
| -------------- | --------------------------- |
| `show_id`      | Unique ID of each title     |
| `type`         | Movie or TV Show            |
| `title`        | Title name                  |
| `director`     | Director name               |
| `cast`         | Cast members                |
| `country`      | Country of production       |
| `date_added`   | Date added to Prime Video   |
| `release_year` | Original release year       |
| `rating`       | Age rating                  |
| `duration`     | Movie duration / TV seasons |
| `listed_in`    | Genres                      |
| `description`  | Content description         |

---

## ⚙️ Tech Stack

### Languages & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### Visualization Tool

* Power BI

### Concepts Used

* Data Cleaning
* Missing Value Handling
* Duplicate Removal
* Exploratory Data Analysis (EDA)
* Business Intelligence Dashboarding
* Data Storytelling

---

## 🔍 Project Workflow

### 1. Data Cleaning

* Removed duplicate records.
* Handled missing values.
* Standardized country and genre fields.
* Prepared cleaned dataset for visualization.

### 2. Exploratory Data Analysis

Performed analysis on:

* Movies vs TV Shows
* Top Genres
* Top Countries
* Ratings Distribution
* Release Year Trend
* Content Growth

### 3. Dashboard Creation

Built an interactive Power BI dashboard including:

* KPI Cards
* Donut Chart
* Bar Charts
* Area Chart
* World Map
* Interactive Filters (Slicers)

---

## 📈 Key Insights

### 🎥 Movies dominate the platform

Movies represent the majority of Amazon Prime Video's content library compared to TV Shows.

### 🌍 United States leads content production

The United States contributes the highest number of titles, followed by other major content-producing countries.

### 🎭 Drama is the most common genre

Drama appears as the most frequently listed genre across the catalog.

### 📅 Rapid content growth after 2010

The number of titles released and added to the platform increased significantly during the last decade.

### 🔞 13+ rated content is highly prevalent

Most titles fall under family-friendly and teenage audience ratings.

---

## 📊 Dashboard Features

The Power BI dashboard provides:

* Total Titles KPI
* Movies KPI
* TV Shows KPI
* Genre Breakdown
* Country-wise Content Distribution
* Ratings Analysis
* Release Year Trend
* Interactive Filters for:

  * Genre
  * Country
  * Release Year

---

## 📂 Repository Structure

```text
Amazon-Prime-Videos-Analysis/
│
├── amazon_prime_titles.csv          # Raw dataset
├── prime_video_analysis.ipynb       # Python EDA notebook
├── prime_video_cleaned.csv          # Cleaned dataset
├── Amazon Prime Dashboard.pbix      # Power BI Dashboard
├── dashboard_preview.png            # Dashboard screenshot
└── README.md                        # Project documentation
```

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Priyanshu-Singh1045/Amazon-Prime-Videos-Analyis.git
cd Amazon-Prime-Videos-Analyis
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Notebook

```bash
jupyter notebook prime_video_analysis.ipynb
```

### Open Power BI Dashboard

Open the `.pbix` file in **Power BI Desktop** and connect it to the cleaned CSV if required.

---

## 💡 Business Value

This project demonstrates how data analytics can help streaming platforms:

* Understand content distribution.
* Identify popular genres and audience categories.
* Track production trends across years.
* Explore geographic content availability.
* Build interactive dashboards for decision-making.

---

## 🧠 Skills Demonstrated

* Data Cleaning & Transformation
* Exploratory Data Analysis (EDA)
* Python Data Analysis
* Power BI Dashboard Development
* Data Visualization
* Business Insight Generation
* Storytelling with Data

---

## 📬 Connect With Me

**Priyanshu Singh**

* GitHub: https://github.com/Priyanshu-Singh1045
* LinkedIn: [www.linkedin.com/in/priyanshu-singh1045](http://www.linkedin.com/in/priyanshu-singh1045)

---

⭐ If you found this project useful, consider giving the repository a **Star**.
