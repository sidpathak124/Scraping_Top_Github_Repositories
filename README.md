# Objective:
To scrape github website to find information on top most trending repositories, for every topic.

**Steps we followed:**
- We scrape a complete list of all the topics on Github. 
- For each topic, we'll get topic title, topic page URL and topic description.
- Further, for each topic `(180 of them)`, we will collect the top 30 repositories.
- For each repository, we'll collect the repo name, username, number of stars and repo URL.
- We collect and store all of these info in a csv format. We assign a separate csv file for each topic

**Python libraries used**
- Requests 
- BeautifulSoup
- Pandas
