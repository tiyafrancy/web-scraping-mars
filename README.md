# Module 11 Challenge      

This module challenge is divided into 2 parts. In the first part, we scrape the title and preview text from Mars news articles. In the second part, we use the data provided by the Curiosity Mars rover, to scrape and analyze Mars weather.


## Part 1: Scrape Titles and Preview Text from Mars News

We use "part_1_mars_news.ipynb" Jupyter notebook to complete this challenge. First, we need to install 'browser driver' according to your system. Here, I have used **chromedriver** to complete my challenge. To import the 'Browser' class from the Splinter library, we have to use the code **pip install splinter** in the terminal to install the splinter library. Then write **from splinter import Browser** in the jupyter notebook.     
                  
Website we used for scraping data is stored under the name 'url'. url = 'https://static.bc-edx.com/data/web/mars_news/index.html'        
                  
To extract data from the website using Beautiful Soup, we must install the library. We can do this by the command,**pip install beautifulsoup4** in the terminal. Once we installed Beautiful Soup, we can import it into our jupyter notebook by using the code **from bs4 import BeautifulSoup**. Then we can create a Beautiful Soup object to complete this challenge.   

After completing the web scraping we can close the browser by using the code : browser.quit()
              

        
             
