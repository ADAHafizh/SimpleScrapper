# Simple Web Scrapper

### Description

This is a simple website scrapper (https://www.dicoding.com/academies/list), with certain scrapping target elements in mind. It uses Selenium and BeautifulSoup to extract course information from Dicoding's academy listing page. It collects data such as course name, duration, rating, level, summary, total modules, and total students, then saves the results in a JSON file. The scraper runs in headless mode using Firefox and includes basic error handling for missing elements.

### Requirements

- Selenium (https://www.selenium.dev/documentation/)
- BeautifulSoup (https://pypi.org/project/beautifulsoup4/)
