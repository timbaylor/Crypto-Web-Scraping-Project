# Crypto-Web-Scraping-Project

Utilizes the HTML parser "BeautifulSoup" and the library "openpyxl" to scrape the current top 5 cryptocurrencies in the world from https://www.coingecko.com/ along with important statistics such as the current price, percentage change in the last 24 hours, and the price based on the percentage change. The information is then exported to a well formatted Excel spreadsheet report.

Furthermore, for Bitcoin and Ethereum, the program alerts you via text (through Twilio) if the value increases or decrease within $5 of its current value.

For the twilio_keys file, please enter your personal API key information, Twilio number, and personal number. A Twilio account is required for this section of the program.
