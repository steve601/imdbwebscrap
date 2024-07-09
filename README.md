## IMDB MOVIES WEB SCRAPING PROJECT

### Overview
This project involves web scraping to extract valuable data from a imdb movies website for further analysis,this project is built using Python with BeautifulSoup library

### Features
**Data extraction using BeautifulSoup**
**Storing extracted data in a pandas DataFrame**
**Flexible configuration for different websites**
### Installation
**Clone the repository:**

git clone https://github.com/yourusername/imdbwebscrap.git
cd web-scraping-project
**Create and activate a virtual environment (optional but recommended):**

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
**Install the required dependencies:**

pip install -r requirements.txt
**Usage**
Configure the scraper:
Edit the config.ipynb file to match the structure of the target website.

*Output file name and path*
Data Extraction
The scraper collects the following data from each page:

House names
Locations
Image URLs
Prices
*The data is stored in a pandas DataFrame and exported to a CSV file.*

### Dependencies
Python 3.x
Selenium
BeautifulSoup4
pandas
numpy


