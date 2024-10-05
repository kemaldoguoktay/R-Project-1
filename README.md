# 📝R-Project-1

This repository contains an R project analyzing various datasets and performing data manipulations. The tasks include downloading and processing datasets, performing statistical analysis, data visualization, and web scraping.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Usage](#usage)

## Overview
The project is divided into multiple questions that focus on different aspects of R programming:
1. **Data Extraction and Transformation** using shell commands like `wget`, `mv`, `sed`, and `awk`.
2. **Statistical Analysis** and **data manipulation** using `tidyverse` libraries in R.
3. **Data Visualization** using `ggplot2` for time series analysis.
4. **Web Scraping** to extract real-time earthquake data using `rvest` and visualizing fuel station locations using `leaflet`.

### Key Tasks:
- Processing and analyzing college scorecard and chocolate ratings datasets.
- Grouping data by specific columns and summarizing the results (mean, median, range).
- Visualizing relationships between temperature and time, including seasonal trends.
- Web scraping and creating interactive maps for earthquake and fuel station data.

## Requirements
Make sure you have the following R libraries installed to run the project:
```r
# For data manipulation and visualization:
install.packages(c("tidyverse", "dplyr", "ggplot2", "lubridate", "magrittr", "leaflet"))

# For web scraping and geographic data:
install.packages(c("rvest", "sf", "rnaturalearth", "httr", "xml2", "RgoogleMaps", "maps", "mapdata"))

## Setup
1. **Download the datasets:**
   - The data used in this project includes:
     - [College Scorecard Dataset](https://raw.githubusercontent.com/dhavalpotdar/College-Scorecard-Data-Analysis/master/MERGED_2017_2018_cleaned.csv)
     - [Chocolate Dataset](https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2022/2022-01-18/chocolate.csv)
     - A custom dataset for temperature data (`chicago-nmmaps-custom.csv`).
   
   Download the required datasets and place them in your working directory.

2. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/R-Project-1.git
   cd R-Project-1
   ```

3. **Load the necessary libraries:**
   Open the R script and ensure all necessary packages are installed and loaded.

## Usage
The R scripts in this project perform various operations on the datasets:

### Question 1: Working with College Scorecard Data
- **Shell Commands:** Downloads, processes, and filters data using shell commands like `wget`, `sed`, and `awk`.

### Question 2: Chocolate Ratings Data Analysis
- **Data Manipulation:** Group and summarize chocolate rating data by company location.
- **Statistical Summary:** Calculate mean, standard deviation, and range of chocolate ratings.
- **Data Visualization:** Use `ggplot2` to visualize patterns in chocolate ratings based on different factors like company location and cocoa percentage.

### Question 3: Temperature Analysis
- **Seasonal Trend Analysis:** Visualize the relationship between date and temperature, grouped by season.
- **Correlation Analysis:** Explore the relationship between temperature and dew point.

### Question 4: Web Scraping and Geographical Data Visualization
- **Web Scraping:** Extract earthquake data from an online source and classify the events based on their magnitude.
- **Map Visualization:** Use `leaflet` to create interactive maps of earthquake locations and fuel stations.
This `README.md` provides a clear structure for your project, including setup instructions, usage details, and an overview of each task. Let me know if you'd like to modify or expand any section!
