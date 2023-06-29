# LinkedIn_Bot
This project is a LinkedIn bot that automates the process of searching for public profiles on LinkedIn and exporting the data to an Excel sheet. 
The bot signs in to LinkedIn on behalf of the user, takes a search query from the user, and generates an output file containing information about the 
public profiles that match the search criteria.

## Features
- Automated sign-in to LinkedIn using user credentials.
- Ability to input a search query to find relevant public profiles.
- Scrapes data from LinkedIn profiles, including name, job title, location, and profile URL.
- Exports the collected data to an Excel sheet for further analysis.

## Libraries and Modules
1. <b>selenium </b> : To interact with web browser
2. <b>chromedriver </b>: For selenium to interact with
3. <b>beautifulsoup4 </b>: To scrape content of the website
4. <b>time </b>: To delay an action by specific amount of time
5. <b>csv </b>: To work with csv files

## Installation 
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/linkedin-bot.git
   ```
2. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```
3. Run the scarper.py file to start the bot:
   ```
   python scraper.py
   ```
## Limitations
The bot relies on web scraping techniques and is subject to LinkedIn's terms of service and scraping limitations. Use it responsibly and be aware of any potential legal and ethical implications.</br>
LinkedIn's website structure may change over time, which can break the bot's scraping functionality. Regular maintenance and updates may be required to keep the bot working properly.

## Contributing
Contributions are welcome! If you encounter any issues or have ideas for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. This project is intended for educational and personal use only. The author is not responsible for any misuse or violation of LinkedIn's terms of service. Use this bot at your own risk.
   

