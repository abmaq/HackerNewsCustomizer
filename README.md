# Web scraping with Beautiful Soup (HackerNews Customizer)

# Project Overview
HackerNews Customizer is a Python application designed to enhance your experience with Hacker News, an influential platform for technology news and discussions. 
This application allows you to download the titles, links, and votes from the first page of Hacker News, providing you with curated content in descending order 
based on votes.Hacker News serves as a curated source of high-quality content and discussions related to technology, startups, and programming. Its active moderation and 
voting system help surface interesting and substantive articles and conversations. Being featured on the front page of Hacker News can drive significant 
traffic and attention to a website, product, or project, making it valuable for startups, developers, and content creators in the tech space. Additionally, 
the critical and discerning audience of Hacker News lends credibility and validation to technologies and ideas, while influential figures in the tech 
industry actively participate in discussions, making it a platform for sharing ideas and engaging with the community.

# Methodology
## i. Setting Up the Project
Installing necessary dependencies.
Importing required libraries.

## ii. Scraping Hacker News with BeautifulSoup
     Using requests to fetch the HTML content of Hacker News.
     Parsing the HTML content with BeautifulSoup.
     Selecting relevant elements (titles, links, votes) using CSS selectors.

## iii. Sorting Stories by Votes
     Defining a function to sort stories by their votes.
     Utilizing Python's sorted() function and lambda functions.

## iv. Building the Custom Hacker News List
     Combining titles, links, and votes into a custom Hacker News list.
     Filtering stories based on vote count.

## v. Putting It All Together: HackerNews Customizer Application
    Creating a Python script that integrates all the steps above.
    Running the script to generate the custom Hacker News list.
