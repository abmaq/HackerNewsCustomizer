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
The HackerNews Customizer application follows a straightforward methodology to provide users with curated content from Hacker News. Here's how it works:

## 1. Fetching HTML Content: 
The application sends a GET request to the Hacker News website using the requests module to retrieve the HTML content of the first page.

## 2. Parsing HTML: 
Using BeautifulSoup, the application parses the HTML content obtained from the response.

## 3. Selecting Relevant Elements: 
The application selects all links with the class 'titleline' and all elements with the class 'subtext' using CSS selectors. 
These elements contain the titles, links, and votes for the stories on the page.

## 4. Sorting Stories by Votes: 
The application defines a function (sort_stories_by_votes()) to sort the retrieved stories based on their vote counts in descending order.

## 5. Creating Custom Hacker News List: 
Another function (create_custom_hn()) is defined to create a custom Hacker News list by iterating through the selected links and subtext elements. 
It extracts the title, link, and votes for each story, filters out stories with less than 100 votes, and appends them to the list.

## 6. Printing Custom Hacker News List: 
Finally, the application prints the custom Hacker News list using the pprint module, providing users with a curated selection of stories from Hacker News.

# Features

Retrieves titles, links, and votes from the first page of Hacker News.
Presents curated content in descending order based on votes.
Enhances the Hacker News experience by providing streamlined access to high-quality content and discussions.

# Contributions
Contributions to HackerNews Customizer are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.
