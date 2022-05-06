# SQL-Final-Project
Project Name: Netflix-Animation-Analytics

## Project Objective: 
## What problem are you solving?
I want to find data that would show the current trends in Animated films and TV shows to see how Netflix could expand the retention of its Animation fans and potentially find genres or themes that are topical yet are not being fully capitalized on. 

## How are you solving this problem?
I explored social media platforms such as Twitter and Reddit using an API to explore trends for films and shows, capturing current interests that may stay relevant for the next few years, and explore reviews for Netflix’s current content and see where fans may find disinterest or a lack in quality performing some web scraping on sites like IMBb.

## Job Description
Development Analyst is the position I chose with Netflix' animation department. The responsibilities involve budgeting and handling cash flows for films in development, as well as creating monthly reports to summarize the trends, progress, and health of overall film development slate. This project was supposed to go in depth with current animations and see how Netflix can potentially target more profitable films to produce in its animation department. Unfortunately, it was very difficult to come close to the preferred findings, yet I was able to find info to focus on current movies they have, and emphasize actions towards their existing content. 

## Data Sources:
### https://www.kaggle.com/datasets/shivamb/netflix-shows 
This data source was used for my netflix_titles table. Just go ahead and download the file there.
show_id INT NOT NULL AUTO_INCREMENT,
	type,
	title,
	country,
	date_added,
	release_year,
	rating,
	duration,
	listed_in,
	description,
	PRIMARY KEY (show_id)
### https://medium.com/geekculture/utilizing-reddits-api-8d9f6933e192 
This data source was used to learn how to run the reddit API. Follow the instructions carefully.
	post_id INT NOT NULL AUTO_INCREMENT,
	author,
   	title,
    flair,
    post_body,
    score,
    upvote_ratio,
    ad_generated,
    mod_note,
    created_utc_date,
    link,
    PRIMARY KEY (post_id)
### https://datasets.imdbws.com/ 
This link takes you to IMDB tables. Be careful though, these are .tsv and may need to be converted to .csv to transfer into your database. Tables: 
name.basics.tsv.gz
title.akas.tsv.gz
title.basics.tsv.gz
title.crew.tsv.gz
title.episode.tsv.gz
title.principals.tsv.gz
title.ratings.tsv.gz

Links to the notebook and a description of the notebook's purpose

## Future Improvements:
With more time, I would have liked to implement my Twitter API. I was able to figure it out to the last degree, but by the time it was ready, I couldn't use it. My biggest lesson would be to request for elevated permissions on the API in order to properly use it. Additionally, I started this project expecting to use the Netflix API to gather data on revenue and gross profit from cetain films, but halfway through this project, I found out that Netflix had shut down their API a few years ago. So in response, I would have wanted to take more time to look at tables for revenue of either movies and shows on Netflix or find data on the box office sales in movie theaters for certain movies. I had a difficult time finding tables specificially pertaining to Netflix subscriptions or revenue of any kind, so being more creative on profits would have been detrimental.

