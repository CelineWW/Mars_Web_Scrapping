# Mission-to-Mars

## Overview of mission-to-mars analysis
To get the latest news and updates of Mars, web scraping was used to gather the latest data. 
1.  Use ChromeDriverManager, BeautifulSoup and Splinter to scrape Latest Mars news, Featured Mars Images, Mars Facts, and High-resolution images and titles of Mars Hemisphere
2.  Store the scraped data on a Mongo database, and use Flask to set up the route for the webpage.
3.  Create index.html as webpage template and all gathered data would be displayed on this page.
4.  Set up a *Scrape New Data* button to triggle scarping process.
5.  Update web app to make it mobile-responsive, and alter some Bootstrap 3 components to make it stand out.

## Results
- **Latest Mars news**

![Latest Mars News](https://user-images.githubusercontent.com/105877888/182433198-24626911-1d42-47fd-987e-42a73129e3fc.PNG)

- **Featured Mars Images**

![Featured Mars Image](https://user-images.githubusercontent.com/105877888/182433349-f4f9d72d-f047-4034-9d99-4b721d6d0a9d.PNG)

- **Mars Facts**

![Mars Facts](https://user-images.githubusercontent.com/105877888/182433409-febe83cf-4f42-4f51-8750-414e84b65d37.PNG)

- **Mars Hemisphere**

![hemisphere_image_urls](https://user-images.githubusercontent.com/105877888/182433594-aaa10f81-8ef6-48a4-8fba-1db0a222fe2e.PNG)

![HR Hemisphere images](https://user-images.githubusercontent.com/105877888/182433629-06757876-3310-4be2-ad00-95c1bd811957.PNG)

- **Device Responsible Web App**
  - Desktop webpage
    
![index webpage](https://user-images.githubusercontent.com/105877888/182433665-1733cf4b-d1f6-4768-b765-72cdfda018e0.PNG)


  - Mobile webpage
 
![mobile website](https://user-images.githubusercontent.com/105877888/182434012-6ea94eae-b2c0-4d28-a73f-59434689b522.PNG)


## Summary

  - Lowest temperature shows a big difference in June and December. However, the lowest temperature mostly happen in mid-night. The   surf and ice cream shop opens in day. Highest temperature doesn't change too much. So, this won't affect W. Avy's bussiness dramatically.
  - Even though the average temperature in December is slightly cooler than June overall. It is still very mild weather in Oahu throughout the year. Perfect temperature for surfing and having ice cream.
  - Since Oahu is an island, surrounded by the ocean. Precipitation is a critial parameter of the weather too. We can do queries of precipitation data for the months of June and December from Measurement table. Ultilize the summary statistics of precipitation data to get more information.
  - From location to location, the weather is variable too. There are multiple stations for detecting temperature and precipitation. So do the query from Station table to get the tempearature and precipitation differences among stations would help too. We will suggest W. Avy to operate his surf and ice cream shop closer to the station at which fit his target weather better.
