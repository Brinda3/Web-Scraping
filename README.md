# Web-Scraping
Scraping GitHub topics website.
PREREQUISITES: PYTHON, BASICS OF HTML CSS, BASIC NETWORK KNOWLEDGE to understand the project better.
TOOLS: PYTHON, REQUESTS, PANDAS, BEAUTIFUL SOUP

### Here are the steps to follow:
- To scrape https://github.com/topics
- To get a list of topics.for each topic tittle, topic page URL and topic description.
- for each topic, we'll get the top 25 repositories in the topic from the topic page
- for each topic we'll grab the repo name, user name, stars and repo URL
- for each topic we'll create a CSV file.

Created this project in Jovian:
jovian link: https://jovian.ai/brindaparthiban13/scraping-github-topics-repositories-5a873


## Scrape the list of topics from Github
- use requests to downlaod the page
- user BS4 to parse and extract information
- convert to a Pandas dataframe

To get topic titles, we can pick `p` tags with the `class` ...

![](https://i.imgur.com/OnzIdyP.png)

## Atlast Putting it all together

- We have a funciton to get the list of topics
- We have a function to create a CSV file for scraped repos from a topics page
- Let's create a function to put them together


## References and Future Work

Summary of what we did
- First we scraped the topics from the www.github.com/topics
- Then we scraped the top repositories for each topics
- References to links you found useful

usefull links
- www.crummy.com
- www.geeksforgeeks.org

Ideas for future work

- deploying a web scraping project from scratch using Python, Selenium, and AWS Lambda.


   
    
    
