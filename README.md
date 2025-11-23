# IMDb-Movie-Rating-Scraper
A Python automation project that scrapes Top 250 Movies from IMDb using Selenium and stores the extracted data in CSV format with visual charts.
Project Overview

The IMDb Movie Rating Scraper automatically extracts movie information such as:

Movie Title

Release Year

Ranking

IMDb Rating


The scraper uses Selenium WebDriver to dynamically load and capture JavaScript-rendered content from IMDb.


---

🛠 Tech Stack

Python

Selenium

WebDriver Manager

Pandas

Matplotlib



---

⭐ Features

Dynamic scraping using Selenium

Extracts full movie details from IMDb Top 250

Saves clean data to CSV

Generates visual charts

Easy to extend for genres, cast, and movie info



---

📊 Project Output

movies.csv → Contains full movie data

rating_chart.png → Ratings visualization

year_chart.png → Release year visualization



---

🚀 How to Run

pip install selenium pandas matplotlib webdriver-manager
python imdb_scraper.py


---

📂 Folder Structure

IMDb-Scraper/
│── imdb_scraper.py
│── movies.csv
│── rating_chart.png
│── year_chart.png
└── README.md


---

📌 Future Enhancements

Scrape movie genres

Scrape cast & director

Build dashboard using Flask

Add machine learning recommendation model
