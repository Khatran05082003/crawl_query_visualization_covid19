# COVID-19 Data Pipeline Project

This project aims to gather, clean, analyze, and visualize COVID-19 cases and deaths data worldwide. Below is an overview of the project files and their roles:

## Project Files

### CRAWL_CLEANING.ipynb

- **Purpose:** Python notebook for web scraping COVID-19 data and cleaning it.
- **Usage:** Use this notebook to extract raw data from online sources and perform initial data cleaning steps.

### EDA.ipynb

- **Purpose:** Exploratory Data Analysis (EDA) notebook.
- **Usage:** Analyze the cleaned COVID-19 data to derive insights and prepare for database integration.

### QUERY.ipynb

- **Purpose:** Notebook for connecting to MySQL database, creating tables, importing data, and querying.
- **Usage:** Establish database connectivity, create schema, import cleaned data into MySQL, and perform SQL queries.

### Covid-19.csv

- **Purpose:** CSV file containing cleaned COVID-19 data.
- **Usage:** Data exported after cleaning for further processing and database insertion.

### Dashboard.png

- **Purpose:** Dashboard visualization image.
- **Usage:** Preview of the Tableau dashboard created from the MySQL data for COVID-19 insights.

## Project Workflow

1. **Data Crawling and Cleaning:** Use `CRAWL_CLEANING.ipynb` to scrape COVID-19 data, clean it, and export to `Covid-19.csv`.
   
2. **Exploratory Data Analysis:** Utilize `EDA.ipynb` to perform in-depth analysis of the cleaned data, identifying trends and patterns.

3. **Database Integration:** Use `QUERY.ipynb` to connect to MySQL, create a database schema, import `Covid-19.csv` data, and execute queries for further insights.

4. **Dashboard Creation:** Visualize insights in `Dashboard.png` using Tableau, leveraging data stored in MySQL database.

## Usage

- Clone the repository.
- Open and run the notebooks in the specified order (`CRAWL_CLEANING.ipynb`, `EDA.ipynb`, `QUERY.ipynb`).
- Ensure MySQL is installed and configured as per the instructions in `QUERY.ipynb`.
- Use Tableau to import data from MySQL and create visualizations based on `Dashboard.png`.

Feel free to modify the notebooks and dashboard to suit specific analysis needs or data updates.
![Dashboard](https://github.com/user-attachments/assets/ff5fd249-6590-4fe1-8de9-0789fe651477)
