# -Linkedin-job-description-scrapper

1) An important skill in Data Science is to get data, in this case, from websites. Also called web scraping, this process uses lines of codes that will access selected web pages and scrap all kinds of data you desire.</br>
In this project, we will **access the LinkedIn webpage**, send login credentials, access data scientists jobs, scrap jobs requirements, and plot a wordcloud that shows us what are the most requested requirements by companies.</br>

2)To simplify the scrape process, we will use two python libraries:
- Selenium
- BeautifulSoup

## Selenium
Selenium is a powerful python framework that permits us to make web browser automation with few line codes. To install Selenium write the command below on your terminal:</br>
`pip install selenium` </br>
</br>
Selenium needs a ‘web driver’ to work. Google for example ‘selenium chrome web driver download’ (change chrome for a browser that you want to use), download and put the file on the same directory of your python script. In my case, I used google chrome, but you can do the same process to others browsers.


![Screenshot 2022-03-05 144953](https://user-images.githubusercontent.com/84931642/156877069-da26918c-2313-4e79-b85e-5e2465ee3918.png) </br>
Check your browser version before downloading the proper file.
![Screenshot 2022-03-05 145148](https://user-images.githubusercontent.com/84931642/156877117-953c1a35-2581-4ee2-bd0a-cb2ada8ceaa5.png)</br>

## Beautifulsoup
We will use Beautfulsoup to get the data (text, tables, imgs, etc) from websites. Command to install:</br>
`pip install beautifulsoup4` </br>
This tool doesn’t work in a simple way when there are javascript functions in websites. That's why we will use Selenium + BeautifulSoup, the first one will manipulate inputs, clicks, scrolls and the second will get all data that we want.
Now, we are ready to start our code. First, we’ll import the python libraries that we’ll use:
