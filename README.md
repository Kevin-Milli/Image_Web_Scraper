# Image Scraper
This Python script scrapes images related to a given search term from Unsplash and saves them to a specified destination folder.<br> 
It utilizes BeautifulSoup for web scraping and the requests library for making HTTP requests.

## Installation
1. Clone this repository: `git clone https://github.com/Kevin-Milli/Image_Web_Scraper.git`
2. Navigate to the project directory: `cd your-repository`
3. Install the required dependencies: `pip install requests beautifulsoup4`

## Usage
Run the script `image_scraper.py` with Python and provide a search term as a command-line argument. For example:<br>
`python image_scraper.py "Artificial Intelligence"`

You can also specify a destination folder where the images will be saved using the `--dest_dir` option. By default, images will be saved in a folder named "images" in the project directory.<br>
`python image_scraper.py "Artificial Intelligence" --dest_dir my_images`

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the LICENSE file for details.
