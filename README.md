📚 Goodreads Web Scraper:

A Python-based web scraping project that extracts detailed information about thousands of books from Goodreads' "Best Books of 2020" list using Selenium. This project collects structured data for exploratory analysis, including book titles, authors, genres, ratings, and more.



🚀 Features:

Scrapes thousands of books across multiple pages.


Gathers rich metadata:

📖 Title

✍️ Author

📅 Publication Year

🌐 Language

⭐ Average Rating

🔢 Number of Ratings

📚 Number of Pages

📖 Genre


📊 Popularity Metrics (Currently Reading, Want to Read):


Cleans and converts fields to numeric format for analysis.

Handles popups, delays, and timeouts gracefully.


🛠️ Tech Stack:

Python

Selenium for dynamic web scraping

Pandas for data handling and cleaning

Chrome WebDriver


📂 Data Fields Collected:

Field	Description
Title	Name of the book
Author	Author of the book
Publication Year	Year the book was published
Genre	Main genre/category
Average Rating	User rating on Goodreads
Number of Ratings	Total number of user ratings
Number of Pages	Page count
Language	Language of the edition scraped
Currently Reading	Users currently reading the book
Want to Read	Users who want to read it
Rank	Position in the "Best of 2020" list


📦 Setup Instructions:

Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/goodreads-scraper.git
cd goodreads-scraper
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the scraper:
Make sure you have Chrome and ChromeDriver installed.

bash
Copy
Edit
python goodreads_scraper.py
Or open the Jupyter notebook Web_scrapping_good_reads.ipynb for a step-by-step execution.

🧠 Author:

Shaikh Ibrahim Rahman

