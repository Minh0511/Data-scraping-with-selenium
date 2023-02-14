# SCRAPE SEARCH AUTO SUGGESTIONS WITH SELENIUM

*Scrape auto suggestions from lazada, shopee, tiki with python and selenium*.

## Pre-requisite

- `python3` version: `3.6.9 or above`
- `pip` version: `21.3.1 or above`

## Usage

__NOTE: These steps below are instructions for Linux environment

- Clone the repository and `cd` inside:
  ``` bash
  git clone https://github.com/Minh0511/Data-scraping-with-selenium.git
  cd Data-scraping-with-selenium
  ```

- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
  
- Run the .py files
  ```bash
  python3 tiki/tiki.py
  ```
  ```bash
  python3 shopee/shopee.py
  ```
  ```bash
  python3 lazada/lazada.py
  ```
  
- The results from search suggestions scraping are stored inside the corresponding json files.
- All 3 files are independent of each other, so they can be run in parallel
