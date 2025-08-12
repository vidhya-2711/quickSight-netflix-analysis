# quickSight-netflix-analysis

📌 Project Overview
This is a **hands-on AWS analytics project** where I analyzed the Netflix Movies & TV Shows dataset using **Amazon S3** for storage and **Amazon QuickSight** for visualization.  
The goal was to uncover insights such as release year trends, country-wise content distribution, and rating patterns.

## Technologies Used
- **Amazon S3** – Cloud storage for datasets
- **Amazon QuickSight** – Business intelligence and data visualization
- **CSV Dataset** – Netflix titles dataset from Kaggle

- ## Hands-On Steps

### 1️. Upload Dataset to Amazon S3
- Created a bucket named `netflix-analysis-bucket`
- Uploaded `netflix_titles.csv`
- Configured permissions for QuickSight to access the bucket

### 2️.Connect S3 Dataset to QuickSight
- Opened **Amazon QuickSight → Datasets → New Dataset → S3**
- Used an **S3 manifest file** to define file location & format
- Connected and prepared the dataset for visualization


### 3.Build & Publish Dashboard
- Combined all visuals into one **interactive dashboard**
- Published and enabled export for reporting

  ## 📊 Final Output
The dashboard includes:
- **Top 20 release years** with the most Netflix titles.
- **Table view** of titles with release year, type, duration, and country.
- **Ratings breakdown** by release year, country, and duration.
- **Category distribution** (e.g., Action & Adventure, Children & Family Movies, Anime Series).
- **Country-wise content count**, with the United States, India, and the United Kingdom as top contributors.


##🏆 Skills Gained
- AWS S3 Bucket Management
- Amazon QuickSight Dashboard Design
- Data Visualization
- CSV Data Analysis

