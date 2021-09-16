---
layout: page
output: html_document
<!-- title: Please Don't Map Twitter -->
---

<!-- # Please Don't Map Twitter -->

[Less than 3% of tweets have location data](proportions.md). However, they are still a great source of information.

For those few tweets that do have location data, it appears when a user tags a place or shares their exact location. 

### Why not?
Beyond being a tiny slice of the Twitterverse, there are several other reasons why you should not map Twitter.

- People are complicated, and they lie. It is not difficult to tell Twitter that you are someplace where you are not.
- Many researchers use Twitter users' self-reported profile location <citation needed>. However, that profile field is free-text and can contain any number of entries that will not map. Mapping based on profile home location creates false locations for anyone tweeting while outside of their home city (assuming their location is a city, such as "Santa Barbara, California," and not something silly like "Trump Town, USA."  Many analysts will fall back on a tweeter's profile location to infer their geographic location. Unfortunately, many people put 'USA' 
or multiple locations as their home location in their profile. 
- Naive or inexperienced spatial analysts will often conflate a place name with its centerpoint. Thus, many Tweets appear to be from a relatively unpopulated part of Kansas because of a large number of Tweets tagged "USA."
- There are complex [ethical and legal ramifications of mapping Tweets](ethics.md). Mapping Tweets can inadvertantly reveal the locations and identities of political dissidents, at-risk individuals, and ordinary people who have not offered their consent to be in your dataset.       

 
### How can I tell?
- Centerpoints or polygons? Tweets that are geotagged will contain an entry, consisting of a geoJSON polygon, from Twitter&#39;s placename dictionary.&nbsp; If users share their exact location, the tweet will contain a geoJSON point. **(insert examples)**

### When can I?
We are not saying never to map a set of Tweets. Public information offices of municipal and county police departments sometimes Tweet out locations of reported crimes. Some firetrucks will Tweet their geolocation then they arrive at a call in order to publicly log a response time. There are any number of useful robots that geotag their Tweets.    
 
[Advice on mapping Tweets](mapping.md)    
