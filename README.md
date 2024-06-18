# Workfile

---
This project is a web scraping tool designed to extract maritime news from the MarineTraffic website. The scraper uses Selenium and Chromium to navigate the site and collect news articles, which are then saved into a CSV file.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Output](#output)
- [Contributing](#contributing)

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You are using a Windows system.
- You have Python 3.x installed.
- You have `pip` installed.

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/maritime-news-scraper.git
    cd maritime-news-scraper
    ```

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download and install Chromium**:
    - Download the latest Chromium build from [Chromium Download](https://download-chromium.appspot.com/).
    - Extract the downloaded file and move the Chromium folder to `C:\Program Files\Chromium`.

4. **Download and install Chromedriver**:
    - Download the Chromedriver that matches your Chromium version from [Chromedriver Downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads).
    - Extract `chromedriver.exe` and move it to `C:\Program Files\Chromedriver`.

## Usage

1. **Run the notebook**:
    - Open the Jupyter Notebook in your preferred environment.
    - Run the cells in the notebook to execute the web scraping script.

2. **Run the script**:
    If you prefer to run the script directly from the command line, you can execute the Python script as follows:
    ```bash
    python scraper.py
    ```

## Output

The scraper will save the collected maritime news into a CSV file named `maritime_news.csv` in the project directory. The CSV file will contain the following columns:
- `Date`: The date when the news was published.
- `Title`: The title of the news article.
- `Content`: The content of the news article.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and passes all tests.
