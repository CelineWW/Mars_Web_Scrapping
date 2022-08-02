# Mission-to-Mars

## Overview of mission-to-mars analysis
To help Robin, who loves astronomy and wants to work for NASA one day, web scraping was used to gather the latest data. 
1. Use ChromeDriverManager, BeautifulSoup and Splinter to scrape Latest Mars news, Featured Mars Images, Mars Facts, and High-resolution images and titles of Mars Hemisphere
2. Store the scraped data on a Mongo database, and use Flask to set up the route for the webpage.
3. Create index.html as webpage template and all gathered data would be displayed on this page.
4. Set up a *Scrape New Data* button to triggle scarping process.
5. Update web app to make it mobile-responsive, and alter some Bootstrap 3 components to make it stand out.

## Results
- **Latest Mars news**
![Latest Mars News](https://user-images.githubusercontent.com/105877888/182433198-24626911-1d42-47fd-987e-42a73129e3fc.PNG)



- **Featured Mars Images**

![december_summary](https://user-images.githubusercontent.com/105877888/180625546-9ef7b818-4031-45bd-bf09-8abb4932bdc4.PNG)
   
- **Mars Facts**
- **Mars Facts**
- **Mars Hemisphere**
  - Highest and Lowest Temperature
     - The highest and lowest temperature in June are 85.0°F and 64.0°F. The highest and lowest temperature in June are 83.0°F and 56.0°F. Lowest temperatrue in December is fairly colder than in June.
     
  - Averager Temperature 
     - The average temperature in June is 74.9°F. The average temperature in December is 71.0°F. December is still slightly cooler than June in Oahu. 
  
  - Standard Deviation
    - Standard Deviation is 3.3 and 3.7 for June and December tempertures respectively. This means that in December, the temperature typically has wider distribution than in June.

## Summary

  - Lowest temperature shows a big difference in June and December. However, the lowest temperature mostly happen in mid-night. The   surf and ice cream shop opens in day. Highest temperature doesn't change too much. So, this won't affect W. Avy's bussiness dramatically.
  - Even though the average temperature in December is slightly cooler than June overall. It is still very mild weather in Oahu throughout the year. Perfect temperature for surfing and having ice cream.
  - Since Oahu is an island, surrounded by the ocean. Precipitation is a critial parameter of the weather too. We can do queries of precipitation data for the months of June and December from Measurement table. Ultilize the summary statistics of precipitation data to get more information.
  - From location to location, the weather is variable too. There are multiple stations for detecting temperature and precipitation. So do the query from Station table to get the tempearature and precipitation differences among stations would help too. We will suggest W. Avy to operate his surf and ice cream shop closer to the station at which fit his target weather better.
