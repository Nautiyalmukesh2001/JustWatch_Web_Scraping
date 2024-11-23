# Web Scraping & Data Handling Project

## Project Description:

This project demonstrates how to scrape movie and TV show data from [JustWatch](https://www.justwatch.com/in/movies?release_year_from=2000), a platform that aggregates content from multiple streaming services. The data scraping is performed using **Selenium**, **BeautifulSoup**, and **Python**. After scraping, we use **Pandas** for data filtering, analysis, and transformation, and finally export the results to CSV files for further use.

---

## Files Included:

- **`Web_Scraping_Data_Handling_Project.ipynb`**: Jupyter/Colab notebook containing the code for web scraping, data analysis, and processing.
- **`movies_df.csv`**: CSV file containing the raw data scraped for movies.
- **`TV_Shows_df.csv`**: CSV file containing the raw data scraped for TV shows.
- **`Movies_filtr_df.csv`**: CSV file containing the filtered movie data (based on release year and IMDb rating).
- **`TV_Shows_filtr_df.csv`**: CSV file containing the filtered TV show data.

---

## Project Tasks:

### **1. Web Scraping:**
- Scrape data for movies and TV shows from JustWatch, including the following attributes:
  - Title
  - Release Year
  - Genre
  - IMDb Rating
  - Streaming Services
  - URL

### **2. Data Filtering & Analysis:**
- Filter the content based on the following criteria:
  - Movies/TV shows released in the last 2 years.
  - IMDb rating of 7 or higher.
- Perform data analysis:
  - Calculate the average IMDb rating for the filtered content.
  - Identify the top genres based on frequency.
  - Determine the most prevalent streaming services.

### **3. Data Export:**
- After filtering and analyzing the data, export the results to CSV files for easy access and further analysis.

---

## Setup and Installation:

### **1. Install Required Libraries:**

Before running the project, install the necessary libraries. You can do this in your Colab environment or your local environment by running:

## Author

* Mukesh Nautiyal
* LinkedIn: [https://www.linkedin.com/in/mukesh-nautiyal-23978a2b1/]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
