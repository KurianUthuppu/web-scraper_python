# Web-Scraper
Extracts content from the requisite web-page and stores in an excel file within the prescribed format

### Basic requirements
* Anaconda / Jupyter  

### Resources
* Reference video - https://www.youtube.com/watch?v=MpF9HENQjDo
* Dataset - https://www.glassdoor.co.in/Job/Home/recentActivity.htm

### Code
- Refer this file -> https://github.com/KurianUthuppu/web-scraper_python/blob/250166440684ef6f1c399299dbd474067b4174c3/Web-Scraper.ipynb
- You can add requisite element of the particular web-page that is to be scraped, to the codeset by:
  - Selecting the particular element in the webpage and right click
  - Select inspect, which will open up the console on the right
  - Select the particular element that is highlighted and right click
  - Click Copy > Copy Xpath; A sample is shown in below pic:
  ![alt text](https://github.com/KurianUthuppu/web-scraper_python/blob/e67c8dc2603e9704bcab7c10a451b1d8c55d930c/Inspect_Element-Web_Page.jpg)
  - Paste the Xpath within this code -> driver.find_element_by_xpath().text
  - Repeat the above step for all elements that you want to scrap from the webpage
  - Store the extracted data in a dataframe and download to an excel sheet as shown in the code 
