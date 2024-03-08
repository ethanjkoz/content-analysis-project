# content-analysis-project
Repo for content analysis project

## Main question: 
- How do the conversational dynamics and post sentiments within online adoption communities differ between general-purpose adoption subreddits like r/Adoption and adoptee-exclusive spaces like r/Adopted? 
- Do adoptees and non adoptees differ in their sentiment towards adoption within these different spaces?

Supplementary questions to answer main:

- Are the topics discussed in r/Adoption and r/Adopted distinctly different from one another? If no, it is not detrimental. But I have a hunch that even though both talk about adoption, they talk about different aspects of it. Since more adopters post in r/Adoption, there are more discussions about the process of adopting. Whereas in r/Adopted there might be more discussion about trauma. 

- Are the posts from adoptees distinctly different from posts not made by adoptees in r/Adopted and r/Adoption? If the answer is no, then the main question becomes much harder to answer. This is a classification question. Because not all users say whether they are adopted or not, it is not easy to understand who is and is not an adoptee when looking at these conversations. 

## (Data)[https://drive.google.com/file/d/1GRo0PJw5vDPCs83xF315R1kLHqbNGAr2/view?usp=drive_link]:
My data comes from the two largest subreddits dealing with adoption: r/Adoption and r/Adopted. The data from the former contains archived posts since its inception as a subreddit as well as more recently scraped data. r/Adopted contains only scrapes the top 1000 most recent posts (due to the limitations of my scraper; I could properly configure selenium to dynamically scrape the website, so I used an older version of reddit to gather conversations by pages). This data contains posts and comments with corresponding metadata like user, flairs, etc. Furthermore, I supplemented the r/Adoption Reddit with more posts from a Reddit archive.

## Methods:
In order to answer these questions there are three distinct methods that I will need to employ. I will need to use ML, specifically neural networks to classify posts made by adoptees and those not made by adoptees. I will incorporate topic modeling to understand the different topics discussed in each subreddit. And then I will perform a sentiment analysis on these topics to discern whether these subreddits are more positive or negative. 
