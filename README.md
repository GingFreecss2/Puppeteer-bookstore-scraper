# Puppeteer Bookstore Web Scraper

This is a simple web scraping project using Puppeteer to scrape a bookstore website, [books.toscrape.com](https://books.toscrape.com/). The project extracts book data, including book title, price, image URL, and rating, and then saves the data to a JSON file.

## High-Level Flow of the Scraper

<p align="center">
  <img src="/flow-diagram.png" alt="High-Level Flow of the Scraper">
</p>

The web scraper follows these high-level steps:

1. **Initialization**: The Puppeteer library is used to launch a headless Chromium browser and open a new page.

2. **Navigation**: The browser navigates to the specified URL, which in this case is [books.toscrape.com](https://books.toscrape.com/).

3. **Data Extraction**: The scraper runs JavaScript code within the web page to extract book data, including titles, prices, image URLs, and ratings.

4. **Data Processing**: The extracted data is processed within the browser, and any necessary data transformations are applied, such as converting prices from strings to numbers and ratings to numerical values.

5. **Data Collection**: The processed data is collected and returned to the Node.js environment.

6. **File Export**: The collected data is saved as a JSON file named `data.json` in the project directory.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch for your feature or bug fix:

## Acknowledgments

- Puppeteer: Puppeteer is a powerful tool for web scraping and automation in the headless Chromium browser.

- [books.toscrape.com](https://books.toscrape.com/): The website used in this project for demonstration purposes.