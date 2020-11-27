# RSelenium-Intro
Introduction to RSelenium running from local binary

In this markdown we will learn to do web scraping using RSelenium. RSelenium provides R bindings for the Selenium Webdriver API. Selenium is a project focused on automating web browsers. RSelenium allows you to carry out unit testing and regression testing on your webapps and webpages across a range of browser/OS combinations. You can access full vignettes of RSelenium [here](https://cran.r-project.org/web/packages/RSelenium/vignettes/basics.html).

R also provide web scrapping tools like the famous `rvest` but RSelenium gives more advantages thant rvest, for example:   
- Java scripted web scrapping   
- Running on selenium server with [Docker](https://www.docker.com/) container   
- Running on local by Webdriver Manager or [wdman](https://docs.ropensci.org/wdman/) wrapper   
- Injectting java script to transform HTML structure    
- Sending Events to elements (click, choose dropdown menu, scrolling, sending text, etc.)   
- Live browsing navigation  
