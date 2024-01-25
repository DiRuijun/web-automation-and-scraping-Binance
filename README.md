# 🪙 Binance_web_automation_and_scraping
This is a program written for extracting key leverage infomation of all currency pairs from Binance website (https://www.binance.com/en/futures/trading-rules/perpetual/leverage-margin).

<img width="800" alt="image" src="https://github.com/Emeryanis/Binance_web_automation_and_scraping/assets/142392109/e4ceeb54-4afe-4788-b077-e2e39c68d8f4">

### API
All trading currency pairs are accessed via MEXC API.
### Web automation
Web is controlled by a Selenium driver to perform recursive actions including click, input and search to retrieve results automatedly for all the currency pairs.
### Web Scraping
Key leverage infomation is extracted from search results, including maximum leverage, position limit for maximum leverage and minimum leverage.
### Dataframe
All the information is stored in dataframe and then output as csv file.
