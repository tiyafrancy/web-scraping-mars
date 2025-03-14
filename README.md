# Module 11 Challenge                
             
This module challenge is divided into 2 parts. In the first part, we scrape the title and preview text from Mars news articles. In the second part, we use the data provided by the Curiosity Mars rover, to scrape and analyze Mars weather.         
            
           
## Part 1: Scrape Titles and Preview Text from Mars News         
            
We use "part_1_mars_news.ipynb" Jupyter notebook to complete this challenge. First, we need to install 'browser driver' according to your system. Here, I have used **chromedriver** to complete my challenge. To import the 'Browser' class from the Splinter library, we have to use the code **pip install splinter** in the terminal to install the splinter library. Then write **from splinter import Browser** in the jupyter notebook.              
                               
Website we used for scraping data is stored under the name 'url'. url = 'https://static.bc-edx.com/data/web/mars_news/index.html'                 
                        
To extract data from the website using Beautiful Soup, we must install the library. We can do this by the command,**pip install beautifulsoup4** in the terminal. Once we installed Beautiful Soup, we can import it into our jupyter notebook by using the code **from bs4 import BeautifulSoup**. Then we can create a Beautiful Soup object to complete this challenge.   
                 
After completing the web scraping we can close the browser by using the code : browser.quit()                 
               
## Part 2: Scrape and Analyze Mars Weather Data           
             
We use "part_2_mars_weather.ipynb" Jupyter notebook to complete this challenge. We are given a table of Mars weather data collected by the Curiosity Mars rover. url = "https://static.bc-edx.com/data/web/mars_facts/temperature.html" is used for the reference. The following analysis has been done:          
                          
#### Minimum Temperature           
          From the data provided by the Curiosity Mars rover, we get to analyze the temperature on Mars.              
Temperature ranges from -68.38 to -83.31. 'Month 8' recorded the maximum temperature, and 'Month 3' recorded the minimum temperature.          
                          
#### Atmospheric Pressure             
          Based on the atmospheric pressure recorded at the Curiosity's location, we can clearly state that the 'Month 9' with an average pressure of 913.31, has the maximum pressure recorded, and the 'Month 6' with a pressure of 745.05 has the minimum pressure recorded.            
                               
#### Year Length             
          A martian year is approximately 687 earth days. This is nearly twice as long as an Earth year, which is about 365 days.             
             

After the analysis, we have exported the DataFrame to a CSV file. mars_data.csv contains the exported data. Close the browser by using the code : browser.quit()                           
          
# Acknowledgment               
                
I have done this assignment using the help of some internet searches and some help from my SMU Instructor.
   


              

        
             
