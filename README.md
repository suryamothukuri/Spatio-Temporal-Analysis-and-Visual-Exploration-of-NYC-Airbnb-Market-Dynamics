# Exploratory Data Analysis and Visualization of NYC Airbnb Data

This repository contains an exploratory data analysis and visualization project on the **New York City Airbnb Open Data** dataset. The project studies how Airbnb listings vary across NYC boroughs and neighborhoods by examining listing density, price distribution, room types, host behavior, minimum-night policies, reviews, availability, and geospatial patterns.

The analysis was completed as part of **INFO-I 590 Data Visualization** at Indiana University Bloomington.

## Project Overview

Airbnb is a major part of the short-term rental ecosystem in New York City. Because listing prices, availability, room types, and host strategies vary widely by location, exploratory data analysis can help reveal how the NYC Airbnb market behaves across boroughs such as Manhattan, Brooklyn, Queens, the Bronx, and Staten Island.

This project uses Python-based data analysis and visualization techniques to answer questions such as:

- Which NYC boroughs have the highest concentration of Airbnb listings?
- How do listing prices vary by borough and room type?
- Are Manhattan and Brooklyn consistently more expensive than other boroughs?
- How do minimum-night requirements differ across host listing counts and neighborhoods?
- What words are most commonly used in Airbnb listing names?
- How do reviews, availability, and pricing interact across boroughs?
- How can interactive maps help users explore Airbnb listing patterns geographically?

## Dataset

The project uses the `NYC_Airbnb.csv` dataset, which contains **48,895 listings** and **16 columns**.

Key columns include:

| Column | Description |
|---|---|
| `id` | Unique listing ID |
| `name` | Listing title/name |
| `host_id` | Unique host ID |
| `host_name` | Host name |
| `neighbourhood_group` | NYC borough |
| `neighbourhood` | Specific neighborhood |
| `latitude` | Listing latitude |
| `longitude` | Listing longitude |
| `room_type` | Type of listing, such as private room or entire home/apartment |
| `price` | Listing price |
| `minimum_nights` | Minimum nights required for booking |
| `number_of_reviews` | Total reviews received |
| `last_review` | Date of latest review |
| `reviews_per_month` | Average monthly review count |
| `calculated_host_listings_count` | Number of listings managed by the host |
| `availability_365` | Number of available days in a year |

## Repository Structure

```text
.
├── NYC_Airbnb.csv
├── Mothukuri Surya Teja_Project.ipynb
├── Mothukuri_Surya_Teja_Report.pdf
├── README.md
└── images / generated maps / supporting files
```

Depending on your repo, supporting image files such as city maps or exported visualization images may also be included.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### 2. Move into the project folder

```bash
cd your-repository-name
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn folium plotly pillow notebook
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
Mothukuri Surya Teja_Project.ipynb
```

Run the cells from top to bottom.

## Project Summary

This project demonstrates how exploratory data analysis and visualization can reveal meaningful patterns in the NYC Airbnb market. By combining statistical plots, geospatial maps, correlation analysis, and interactive visualizations, the project provides a detailed view of how location, room type, host behavior, and pricing shape Airbnb activity across New York City.

